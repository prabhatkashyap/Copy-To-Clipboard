Copy-To-Clipboard
=================

><div id="link">http://pkashyap28.wordpress.com
></div>
><a href="javascript:void (0)" id="copy-btn">Copy To Clipboard</a>
>
><script type="text/javascript" src="jquery-1.9.0.min.js"></script>
><script type="text/javascript" src="jquery.zclip.js"></script>
>
><script type="text/javascript">
>    $(document).ready(function () {
>        $("#copy-btn").zclip({
>            path: "ZeroClipboard.swf",
>            copy: function () {
>                return $('#link').html();
>            },
>            beforeCopy: function () {
>            },
>            afterCopy: function () {
>            }
>        });
>    });
></script>
