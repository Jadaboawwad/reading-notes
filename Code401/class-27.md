## 1. Using Models

        in this part we will discuss the following points

* How Django web applications access and manage data ?
* How Model is defiend in Django ?
* What is the use of Django Admin ?

<br/>

                           The beginning of Part One

### 1.1: How Django web applications access and manage data ?

Django web applications access and manage data through Python objects referred to as models. Models define the structure of stored data, including the field types and possibly also their maximum size, default values, selection list options, help text for documentation, label text for forms, etc.

### 1.2 : How Model is defiend in Django ?

Models are usually defined in an application's models.py file. They are implemented as subclasses of django.db.models. Model, and can include fields, methods and metadata. 

```python

from django.db import models

class MyModelName(models.Model):
    """A typical class defining a model, derived from the Model class."""

    # Fields
    my_field_name = models.CharField(max_length=20, help_text='Enter field documentation')
    ...

    # Metadata
    class Meta:
        ordering = ['-my_field_name']

    # Methods
    def get_absolute_url(self):
        """Returns the url to access a particular instance of MyModelName."""
        return reverse('model-detail-view', args=[str(self.id)])

    def __str__(self):
        """String for representing the MyModelName object (in Admin site etc.)."""
        return self.my_field_name

```

### 1.3: What is the use of Django Admin ?

The Django admin application can use your models to automatically build a site area that you can use to create, view, update, and delete records.
<br/>

    
                               The End of Part One

# [BACK TO HOME](https://jehadabuawwad.github.io/reading-notes)

`
