# Notice -  ESLint

Hello <Trainer> ,

In terms of  code Lint, make your scope for today on studying these resource ,

- Read :
    - How to use ESLint with TypeScript : [Link](https://khalilstemmler.com/blogs/typescript/eslint-for-typescript/)
        - Tells you how to lint typescript code in your native HTML/CSS/Javascript code it require a package dependency tracking “package.json” so take care reading it.
        - So go step further in adding this lint service to your application.
        
        ```
        rules: {
        ```
        
        ```
        '@typescript-eslint/adjacent-overload-signatures': 'error',
        ```
        
        ```
            '@typescript-eslint/array-type': 'error',
        ```
        
        ```
            '@typescript-eslint/consistent-type-assertions': 'error',
        ```
        
        ```
            '@typescript-eslint/explicit-function-return-type': 'off',
        ```
        
        ```
            '@typescript-eslint/indent': 'off',
        ```
        
        ```
            '@typescript-eslint/member-delimiter-style': 'off',
        ```
        
        ```
            '@typescript-eslint/member-ordering': 'off',
        ```
        
        ```
            '@typescript-eslint/no-empty-function': 'off',
        ```
        
        ```
            '@typescript-eslint/no-explicit-any': 'off',
        ```
        
        ```
            '@typescript-eslint/no-extra-semi': 'off',
        ```
        
        ```
            '@typescript-eslint/no-misused-new': 'error',
        ```
        
        ```
            '@typescript-eslint/no-namespace': 'error',
        ```
        
        ```
            '@typescript-eslint/no-non-null-assertion': 'off',
        ```
        
        ```
            '@typescript-eslint/no-object-literal-type-assertion': 'off',
        ```
        
        ```
            '@typescript-eslint/no-throw-literal': 'error',
        ```
        
        ```
            '@typescript-eslint/no-unused-expressions': 'error',
        ```
        
        ```
            '@typescript-eslint/no-unused-vars': 'off',
        ```
        
        ```
            '@typescript-eslint/no-use-before-define': 'off',
        ```
        
        ```
            '@typescript-eslint/no-var-requires': 'error',
        ```
        
        ```
            '@typescript-eslint/prefer-for-of': 'error',
        ```
        
        ```
            '@typescript-eslint/prefer-function-type': 'warn',
        ```
        
        ```
            '@typescript-eslint/prefer-namespace-keyword': 'error',
        ```
        
        ```
            '@typescript-eslint/quotes': 'off',
        ```
        
        ```
            '@typescript-eslint/triple-slash-reference': 'error',
        ```
        
        ```
            '@typescript-eslint/unified-signatures': 'error',
        ```
        
        ```
            'constructor-super': 'error',
        ```
        
        ```
            'dot-notation': 'error',
        ```
        
        ```
            eqeqeq: ['error', 'smart'],
        ```
        
        ```
            'func-names': ['error', 'never'],
        ```
        
        ```
            'func-style': ['error', 'expression'],
        ```
        
        ```
            'guard-for-in': 'error',
        ```
        
        ```
            'import-helpers/order-imports': [
        ```
        
        ```
              'error',
        ```
        
        ```
              {
        ```
        
        ```
                alphabetize: { ignoreCase: false, order: 'asc'},
        ```
        
        ```
                groups: ['module', '/^(graphql|orm|shared)/', ['sibling', 'index']],
        ```
        
        ```
                newlinesBetween: 'always',
        ```
        
        ```
              },
        ```
        
        ```
            ],
        ```
        
        ```
            'import/extensions': 'off',
        ```
        
        ```
            'import/no-extraneous-dependencies': 'off',
        ```
        
        ```
            'import/no-unresolved': 'off',
        ```
        
        ```
            'jest/expect-expect': ['error', { assertFunctionNames: ['expect'] }],
        ```
        
        ```
            'jest/no-alias-methods': 'error',
        ```
        
        ```
            'jest/no-disabled-tests': 'warn',
        ```
        
        ```
            'jest/no-focused-tests': 'warn',
        ```
        
        ```
            'jest/no-identical-title': 'error',
        ```
        
        ```
            'jest/no-jasmine-globals': 'error',
        ```
        
        ```
            'jest/no-jest-import': 'error',
        ```
        
        ```
            'jest/no-mocks-import': 'error',
        ```
        
        ```
            'jest/no-test-callback': 'off',
        ```
        
        ```
            'jest/no-test-return-statement': 'error',
        ```
        
        ```
            'jest/no-truthy-falsy': 'error',
        ```
        
        ```
            'jest/prefer-called-with': 'warn',
        ```
        
        ```
            'jest/prefer-to-be-null': 'error',
        ```
        
        ```
            'jest/prefer-to-be-undefined': 'error',
        ```
        
        ```
            'jest/prefer-to-contain': 'error',
        ```
        
        ```
            'jest/prefer-to-have-length': 'error',
        ```
        
        ```
            'jest/require-to-throw-message': 'error',
        ```
        
        ```
            'jest/valid-describe': 'error',
        ```
        
        ```
            'jest/valid-expect': 'error',
        ```
        
        ```
            'jest/valid-expect-in-promise': 'error',
        ```
        
        ```
            'jest/valid-title': 'error',
        ```
        
        ```
            'max-classes-per-file': ['warn', 1],
        ```
        
        ```
            'no-bitwise': 'error',
        ```
        
        ```
            'no-caller': 'error',
        ```
        
        ```
            'no-cond-assign': 'error',
        ```
        
        ```
            'no-console': ['error', { allow: ['warn', 'error'] }],
        ```
        
        ```
            'no-debugger': 'error',
        ```
        
        ```
            'no-empty': 'error',
        ```
        
        ```
            'no-eval': 'error',
        ```
        
        ```
            'no-new-wrappers': 'error',
        ```
        
        ```
            'no-redeclare': 'error',
        ```
        
        ```
            'no-undef-init': 'error',
        ```
        
        ```
            'no-unsafe-finally': 'error',
        ```
        
        ```
            'no-unused-labels': 'error',
        ```
        
        ```
            'no-unused-vars': 'off',
        ```
        
        ```
            'no-use-before-define': 'off',
        ```
        
        ```
            'no-var': 'error',
        ```
        
        ```
            'object-shorthand': 'error',
        ```
        
        ```
            'one-var': ['error', 'never'],
        ```
        
        ```
            'prefer-arrow/prefer-arrow-functions': 'warn',
        ```
        
        ```
            'prefer-const': 'error',
        ```
        
        ```
            'prefer-destructuring': ['error', { array: false, object: true }],
        ```
        
        ```
            radix: 'error',
        ```
        
        ```
            'sort-destructure-keys/sort-destructure-keys': 2,
        ```
        
        ```
            'sort-export-all/sort-export-all': [
        ```
        
        ```
              'error',
        ```
        
        ```
              'asc',
        ```
        
        ```
              {
        ```
        
        ```
                caseSensitive: false,
        ```
        
        ```
              },
        ```
        
        ```
            ],
        ```
        
        ```
            'sort-keys': ['error'],
        ```
        
        ```
            "unused-imports/no-unused-imports": "error",
        ```
        
        ```
            "unused-imports/no-unused-vars": [
        ```
        
        ```
              "warn",
        ```
        
        ```
              { "args": "after-used", "argsIgnorePattern": "^_", "vars": "all", "varsIgnorePattern": "^_" }
        ```
        
        ```
            ],
        ```
        
        ```
            'use-isnan': 'error',
        ```
        
        ```
            'valid-typeof': 'off',
        ```
        
        ```
            '@typescript-eslint/explicit-module-boundary-types': 'off',
        ```
        
        ```
            'import/first': 'error',
        ```
        
        ```
            'import/newline-after-import': 'error',
        ```
        
        ```
            'import/no-duplicates': 'error',
        ```
        
        ```
            'jsx-expressions/strict-logical-expressions': 'error',
        ```
        
        ```
            'linebreak-style': ['error', 'unix'],
        ```
        
        ```
            'no-console': ['error', {allow: ['warn']}],
        ```
        
        ```
            'no-undef': [0],
        ```
        
        ```
            'react/display-name': [0],
        ```
        
        ```
            semi: ['error', 'never'],
        ```
        
        ```
            'sort-keys': ['error'],
        ```
        
        ```
            'sort-destructure-keys/sort-destructure-keys': 2,
        ```
        
        ```
            'simple-import-sort/exports': 'error',
        ```
        
        ```
            'simple-import-sort/imports': [
        ```
        
        ```
              'error',
        ```
        
        ```
              {
        ```
        
        ```
                groups: [
        ```
        
        ```
                  ['^\\u0000'],
        ```
        
        ```
        // side effects
        ```
        
        ```
                  ['^react', '^@?\\w'],
        ```
        
        ```
        // react-* first, then third packages
        ```
        
        ```
                  ['^@(components|constants|modules|utils|hooks|api|screens|navigation|assets|services)(/.*)?'],
        ```
        
        ```
        // absolute imports
        ```
        
        ```
                  ['^(/.*|$)']
        ```
        
        ```
        // relative imports
        ```
        
        ```
                ]
        ```
        
        ```
              }
        ```
        
        ```
            ]
        ```
        
        ```
          }
        ```
        
-