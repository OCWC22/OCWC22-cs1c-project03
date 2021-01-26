The program does the following:
Simulate a Browser
Navigate to URL: link www.google.com
Automate clicking a link
go back to previous pages
Again go back to the javaTpoint website using forward command
Again come back to the Home page using To command
Refresh the Browser using Refresh command
Close the Browser

Description

		CLASS BrowserNavigation:

Simulates a browser's back and forward buttons by recording links that are visited and then keeping a stack of "back" links and a stack of "forward" links.

		CLASS Navigator:

Creates two objects of type StackList

Creates two objects of type StackList class

Returns currentLink

Views and Navigates The current webpage the user is viewing
private String currentLink;

Stacks for back button links and forward links

Two stacks: one for "Back" button links; another for "Forward" button links

		CLASS StackList

Single linked list which implements Iterable

Uses singly linked list implementing Iterable to push() and pop() items
