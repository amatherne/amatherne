Here's a list of tags to style posts:

Change '#' to whatever number it will be
{% sidenote # 'This is a sidenote and *contains a superscript*'%}

without superscript number
{% marginnote 'This is a margin note *without* a superscript' %}

with image
{% marginfigure /img/blog/ '...caption....' %}.


use to disable on mobile
<style type="text/css">
    .sidenote,.marginnote {
        display: none;
    }
    @media screen and (min-width: 550px) {
        .sidenote,.marginnote {
            display: initial;
        }
    }

</style>