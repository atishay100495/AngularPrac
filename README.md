# AngularPrac
Learning AngularJS

MVVM Design Pattern

  Model: Represents and holds raw data. Something that we get directly from database or REST api call
    -Some of its data may be displayed in the view.
    -Can contain logic to retrieve data from some source.
    -Contains NO LOGIC associated with DISPLAYING the MODEL.

  View: HTML and CSS
    Only displays the data that it is given.
    NEVER changes the data.

  ViewModel: Representaion of the state of the view.

Declarative Binder: Declaratively binds the model of the ViewModel to the View.
  Declaratively means u dont have to write any code, the framework does the magic
  Key enabler of the whole MVVM Pattern.

MVVM is a common design pattern for structuring Uis with functionality.


IIFE: Immediately Invoked Functional Expression
