angular-isotope
===============

A library of AngularJS directives for JQuery Isotope. Focussed on using "ng-repeat" to loop through a given array and easily create and populate a multitude of isotope items with a single tile specification.

Works with stable versions of Isotope and Angular. If not, please let me know.


How to use
==========

Install using `bower install angular-isotope`

Include Isotope v1 and Angular in your code as well as the angular-isotope library.

See a no-server-required demo [here](http://mankindsoftware.github.io/angular-isotope/).
View the page source to see how it works.


WilSonic Modifications:
========================
wilsonic-angular-isotope.js : My first attempt to strip out jquery code that prevents angular-isotopes.js from wokring
                              when Jquery plugin is not present.

                              Glaring omission: began to adjust "isoSortbyData" directive, but stop as I began to notice that
                                                walking the dom with angular.forEach is probably not a good solution;

                              myBasic.html represents a demo of what I have created so far

