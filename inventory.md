# Interface Inventory

A breakdown of all of the interface components that should get built out for
this website.

## Login

The login page is unique from the others. It has a different container-level
layout. There's a large floating center heading and a smaller interface box.

* login-page
  * header
  * login-form
    * sign in button

## Logged In

Pages that only appear to authorized users.

* logged-in-page
  * header
    * logo
    * navigation
      * menu item
      * menu item for user with submenu
        * user management panel
  * main
    * "explorer"
      * explorer-item
        * icon
        * heading (h2)
    * view container
      * can have any main component as a child

## Task List

Appears in the view container.

* task list
  * filter
    * state
    * filter-type
    * filter-type
      * has selected variant
  * task section
    * section title
    * task bundle
      * bundle title
      * task
       * icon
        * single and multiple document variants
       * title
       * due date
       * status
       * assigner
       * actions menu

# Task Details

Appears in the view container. A secondary page that is navigated to from other
view pages.

* task details
  * header
    * title
    * actions
      * button
      * button
    * strike
      * approve
      * deny
  * document
    * preview link
    * name
    * filename
      * is a link to download
    * document preview pane
      * hidden by default

# Modals

The modal appears over all of the other screens. It has a grey
semi-transparent border.

## Megamodal

The megamodal has a blue title header and a close button 'x' that floats in the
upper right.

## Confirmation Modal

A smaller modal with a single dismissal button and a message that communicates
the success of an action.

## Document Preview Modal

Displays a document in the center with white text that floats outside.
