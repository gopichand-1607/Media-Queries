### Media-Queries
 
    these are what make modern responsive design possible.

## What is media queries?
     A media query is a specific feature in css that lets you apply styles based on media type.

# Syntax of media query

     - @media screen (min-width:320px) and (max-width:760px)

     @media-specifies media query declaration.

     media type-->It specifies what type of media are we trying to target.
          -screen--->It allows to useValues here, as this makes sense in many of the media types we are trying to match our devices (MATCHES DEVICES SCREENS)
          -all--->Matches all devices
          -print--->It matches documents that are viewed in a print preview or any media that breaks the content up into pages intent to print.

     -Media Features - It defines what features we are trying to match to
          -Desktop---> (min-width:1024px);
          -Tablet---> (min-width:768px) and (max-width:1023px);
          -Smartphones-- > (min-width:340px) and (max-width:767px);

