# Invoice Demo
This is a short demo of the invoicing program I made for the first company I worked for. <br/>
I designed the whole user interface; from the layout, to the feel, to the icons. <br/>
2.5 months to get first production-ready version.<br/>
*Note: screen recordings took away the smoothness of how the application actually behaves IRL*

## Adding
- Create a new invoice by pressing the '+' button. 
- The fields on the form react well to being tabbed through. 
- A user can quickly close the form by pressing 'Esc' or clicking anywhere outside of the form. 

## Deleting
- I made a delete button that removes the need for a confirmation screen.
- Animation is done by mathematically maniuplating an SVG and is tied directly to the press duration.
- Invoice fades into nothing as the user holds down the button to give another level of feedback.

## Filtering 
- The filter button is 'intelligent' as it only allows filtering of the type of invoices that are in the user's list.
- If a user presses, holds, and drags off of the button; the filter is cleared. (I wanted to give a visual feedback to this, but didn't have time)
- Search function works while list is filtered. If the filter is cleared while something is being searched for, it keeps search in place in unfiltered list.

## Loging In
- I created an input box that integrates the label.
- Notice when a user enters in the wrong credentials the input boxes signal this to the user.

## Searching
- I made sure it's still zippy when there are ~20,000 invoices.
- The box goes away nicely.

## Things that were added after I left...
- 'attachment' button inside the invoice card. It's sloppy and shouldn't be above the delete button; it should be a similar looking icon next to it.
- 'Reports' feature that's so bad I'm not even going to bother showing.
- 'description:' inside the invoice card is redundant; the description of the invoice was meant to feel like description.
- I started working on the timeline feature inside the invoice cards, but it wasn't complete before I left and they didn't go the direction I was hoping with it. 



