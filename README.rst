RT Helper
=========

RT Helper is a small Python GTK application that presents a status icon in the GNOME notification area. When a number appears in the primary selection buffer, right-clicking on the icon will present a menu of actions that can be performed on the corresponding RT ticket.

Currently supported actions are:

 * Show ticket in a browser
 * Take (with 'steal' option if already taken)
 * Take and set open
 * Give ticket to another person
 * Disown ticket
 * Move ticket to another queue
 * Change status
 * Punt (take, move queue, give to nobody)