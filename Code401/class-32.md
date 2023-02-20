## 1. DRF Permissions

        in this part we will discuss the following points

* Write Three facts about Permission in Django ? 
* How permissions are determined ?
* Describe Three of API Reference ?

<br/>

                           The beginning of Part One

### 1.1: Write Three facts about Permission in Django ? 

- Permission checks are always run at the very start of the view, before any other code is allowed to proceed. 
- Permissions are used to grant or deny access for different classes of users to different parts of the API.

- The simplest style of permission would be to allow access to any authenticated user, and deny access to any unauthenticated user. This corresponds to the IsAuthenticated class in REST framework.

### 1.2: How permissions are determined ?


Permissions in REST framework are always defined as a list of permission classes.

Before running the main body of the view each permission in the list is checked. If any permission check fails an exceptions.PermissionDenied or exceptions.NotAuthenticated exception will be raised, and the main body of the view will not run.


### 1.3: Describe Three of API References ?

### IsAuthenticated
The IsAuthenticated permission class will deny permission to any unauthenticated user, and allow permission otherwise.

This permission is suitable if you want your API to only be accessible to registered users.

### IsAdminUser
The IsAdminUser permission class will deny permission to any user, unless user.is_staff is True in which case permission will be allowed.

This permission is suitable if you want your API to only be accessible to a subset of trusted administrators.

### IsAuthenticatedOrReadOnly
The IsAuthenticatedOrReadOnly will allow authenticated users to perform any request. Requests for unauthorised users will only be permitted if the request method is one of the "safe" methods; GET, HEAD or OPTIONS.

This permission is suitable if you want to your API to allow read permissions to anonymous users, and only allow write permissions to authenticated users.

<br/>

    
                               The End of Part One

# [BACK TO HOME](https://jehadabuawwad.github.io/reading-notes)
`