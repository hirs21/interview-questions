* Describe the difference between `<script>`, `<script async>` and `<script defer>`.

  `<script>` stops the html parsing while downloading(if external) and executing the script.

  `<script aysnc>` doesn't stop the html parsing while downloading.  Once finished fetching the script parsing stops and it executes.

  `<script defer>` downloads the script during html parsing and will only execute it after parsing is completed, defer scripts are guaranteed to execute in the order that they appear in the html.
