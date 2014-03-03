Controllers
===========
name controllers using names like MyController
Should not know anything about the view they control
Be small and focused
Should not talk to other controllers, use a service
Should NOT own the domain model, use a service
Tthe controller is not the appropriate place to do any DOM manipulation or formatting, data manipulation, or state


Scope/View Model
================
Instead of creating an object and accessing the object directly, reference properties of the object.  Instead of {{name}}, create a $scope.person, then reference {{person.name}}
