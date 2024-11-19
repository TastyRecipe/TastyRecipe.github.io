# TastyRecipy.github.io
This product generates meals for easy meal planning.

Design:
    Describe details of inspections
    Take photos, enter into report
    Take notes on details & photos
    Generate default verbage
    Generate report as PDF or similar for review/sending/filing

 -Describe
    Forms with text areas and text inputs to answer common questions about the review
        (Client info, structure descriptions, problem area descriptions)
    Yes, no checkboxes and multi select (radio and combo boxes)
    Drop downs (Data list or similar) with default verbage that can be edited if needed.
 -Pictures
    Optional button next to each text area to take a picture
    Ability to take several pictures for each area, and additional photos with no text area
    Label pics, to talk about them? ie fig. 1-a fig. 2-a, etc. (# for text area associated, letter for which pic)
 -Report
    Generate nice looking report with all info
    Pictures need to be on a single page, not cut in parts
    Multiple or no pictures for each section of text.

 -Functional
    How to store the pictures, in case of refresh?? (need server??)
        Is web actually a good choice?
        Pros:
         !!     Easy(ish) to build
         !!     Access anywhere on all devices
         !!!    Extremely easy to take pictures and put on site
         !      Learn server code (good on resume`)

        Cons:
         !!!    Potential loss of wifi/coverage in rural areas
         !!!    Refresh could delete ALL data [could store in session variables/cookies?]
         !      unknown how to get stuff out of forms (requires php, which needs server? github can run?)
         !      unknown how difficult (perhaps very) it is to get photos out of website.

    How to actually get pictures
    How to Generate report