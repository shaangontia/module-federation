# module-federation
A Simple Module federation supported application

There are 3 parts to the application

1. Container App : This holds App-1 and App-2 MFEs.
2. App-1 : This is a counter application which increases a count by 1. (1,2,3,4,5,6...)
3. App-2 : Counter application which increases the count multiplied by 2. (1,2,4,8,16...)


I am using Module federation plugin of webpack to bundle the remote applications (app-1 and app-2) and use them as a dependencies inside container app.

Not: This is not a Monorepo structure.
