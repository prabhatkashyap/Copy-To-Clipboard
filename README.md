Copy-To-Clipboard
=================

<div id="link">http://pkashyap28.wordpress.com
</div>
<a href="javascript:void (0)" id="copy-btn">Copy To Clipboard</a>

<script type="text/javascript" src="http://ajax.googleapis.com/ajax/libs/jquery/1.11.1/jquery.min.js"></script>
<script type="text/javascript" src="http://www.steamdev.com/zclip/js/jquery.zclip.min.js"></script>

<script type="text/javascript">
    $(document).ready(function () {
        $("#copy-btn").zclip({
            path: "http://www.zeroclipboard.googlecode.com/svn-history/r10/trunk/ZeroClipboard.swf",
            copy: function () {
                return $('#link').html();
            },
            beforeCopy: function () {
            },
            afterCopy: function () {
            }
        });
    });
</script>
