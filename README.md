STIL WORK IN PROGRESS!
=======================

# Description

jQuery plugin that lets you show the albums and photos from your facebook profile og page.

# Examples

The plugin can be seen live here: [http://beta.thomasclausen.dk/facebook-gallery/](http://beta.thomasclausen.dk/facebook-gallery/)

# Usage

Insert the following code to activate the pluign:

    (function($) {
        $(document).ready(function(){
            $('#facebook_gallery').facebook_gallery({
                id: 'your_id',
                access_token: 'your_access_token',
                count: 10
            });
        });
    })(jQuery);

options:

    id: '' - insert your profile og fanpage id
    access_token: '' - insert your acces token
    count: 10 - any amount from 1-15
    timeout: 400 - any amount (in miliseconds)
    speed: 400 - any amount (in miliseconds)
    effect: 'slide' - choices: 'slide', 'fade' or 'none'
    locale: 'da_DK' - your contry code
    date_format: 'U' - 
    avatar_size: 'thumbnail' - choices: 'low_resolution', 'thumbnail' or 'standard_resolution'
    caption_length: 200, // Any amount you like. Above 0 shortens the message length

# Feedback

I'm self-taught by scattering code across the web, so if you see some bad practices PLEASE contact me, so I can learn from the mistakes I'm making!

Also feel free to contact me if you have som great ideas for improvements.

# License

Credits would be nice, but feel free to use as often as you like.
