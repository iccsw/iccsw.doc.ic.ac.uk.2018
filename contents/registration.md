---
title: Registration
template: page.jade
---

<div id="eventbrite-widget-container-49892101619"></div>

<script src="https://www.eventbrite.com/static/widgets/eb_widgets.js"></script>

<script type="text/javascript">
    var exampleCallback = function() {
        console.log('Order complete!');
    };

    window.EBWidgets.createWidget({
        // Required
        widgetType: 'checkout',
        eventId: '49892101619',
        iframeContainerId: 'eventbrite-widget-container-49892101619',

        // Optional
        iframeContainerHeight: 425,  // Widget height in pixels. Defaults to a minimum of 425px if not provided
        onOrderComplete: exampleCallback  // Method called when an order has successfully completed
    });
</script>

<!--### To be announced-->

<!--<div style="width:100%; text-align:left;"><iframe src="//eventbrite.com/tickets-external?eid=36353086059&ref=etckt" frameborder="0" height="420" width="100%" vspace="0" hspace="0" marginheight="5" marginwidth="5" scrolling="auto" allowtransparency="true"></iframe><div style="font-family:Helvetica, Arial; font-size:12px; padding:10px 0 5px; margin:2px; width:100%; text-align:left;" ><a class="powered-by-eb" style="color: #ADB0B6; text-decoration: none;" target="_blank" href="http://www.eventbrite.com/">Powered by Eventbrite</a></div></div>-->

<!-- <div style="width:100%; text-align:left;" ><iframe
src="//eventbrite.co.uk/tickets-external?eid=18084325705&ref=etckt"
frameborder="0" height="444" width="100%" vspace="0" hspace="0" marginheight="5"
marginwidth="5" scrolling="auto" allowtransparency="true"></iframe><div
style="font-family:Helvetica, Arial; font-size:10px; padding:5px 0 5px;
margin:2px; width:100%; text-align:left;" ><a class="powered-by-eb"
style="color: #dddddd; text-decoration: none;" target="_blank"
href="http://www.eventbrite.co.uk/r/etckt">Powered by Eventbrite</a></div></div> -->
