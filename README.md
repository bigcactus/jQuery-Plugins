# jQuery Plugins

These jQuery plugins have been created to ease the pain that some front-end designers feel when they're trying to implement basic features with little or no JavaScript or jQuery experience.

I plan to add plugins to this repository over time that only require HTML code, data-* attributes, and the inclusion of the script in question, following the same kind of principles as the Twitter Bootstrap extensions, in so far that no coding experience should be required in order to make things work.

I shall improve this README file as time goes by.

## Carousel

Carousel takes simple HTML- and CSS-only carousels and progressively enhances them with features such as page lists, scrolling, class-toggling, timers, timer offsets as well as touch and keyboard events. By following a basic HTML pattern and using some basic CSS, your carousels will also work, to a degree, without JavaScript enabled.

Head to the Carousel folder or visit [the examples page](http://abitgone.github.com/jQuery-Plugins/Carousel) for more information.

## ClassToggle

ClassToggle toggles, on a target element, a single class on and off or between two classes.

Head to the ClassToggle folder or visit [the examples page](http://abitgone.github.com/jQuery-Plugins/ClassToggle) for more information.

## Google Analytics Helper

The Google Analytics helper offers an easy way to track events and pageviews using data attributes.

The helper uses the following attributes to track events:

-   **data-gahelper-event** (required, string)
    The name of the event you'd like to track. Generally speaking, this should be a common definition o the type of user interaction on the element.

-   **data-gahelper-event-category** (required, string)
    The category of events that your event belongs to. This will serve to group the common event definitions you choose.

-   **data-gahelper-event-label** (string)
    An optional label used to further define your event. This can be used to track any additional information for the event you wish to track, such as the name of a video or a file download.

-   **data-gahelper-event-value** (integer)
    An optional value allowing you to track arbitrary numeric data against each event that is triggered.

-   **data-gahelper-event-noninteraction** (true or false)
    Allows you to specify whether or not the interaction that causes the event to be triggered will prevent a 'bounce' in Google Analytics.

To track pageviews, only a single attribute is required:

-   **data-gahelper-url** (required, string)
    The URL you wish to track. This should be site-relative and start with a forward slash.

[Further explanation and examples](http://abitgone.github.com/jQuery-Plugins/GAHelper) are available.
