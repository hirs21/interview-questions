Describe the difference between <script>, <script async> and <script defer>?

<script> stops rendering process, and download and run a script.

<script async> does not stop rendering process while asynchronously downloading a script. When finishing download, it stops rendering and runs the script.

<script defer> does not stop rendering process while asynchronously downloading a script. When finishing rendering, it runs the script.