<html>
    <head>
	    <!-- github calendar css -->
        <link rel="stylesheet" href="plugins/github-calendar/dist/github-calendar.css">
        <!-- github activity css -->    
        <link rel="stylesheet" href="//cdnjs.cloudflare.com/ajax/libs/octicons/2.0.2/octicons.min.css">
        <link rel="stylesheet" href="plugins/github-activity/github-activity-0.1.5.min.css">
        <script type="text/javascript" src="plugins/github-calendar/dist/github-calendar.min.js"></script>
        <!-- github activity plugin -->
        <script type="text/javascript" src="//cdnjs.cloudflare.com/ajax/libs/mustache.js/0.7.2/mustache.min.js"></script>
        <script type="text/javascript" src="assets/plugins/github-activity/github-activity-0.1.5.min.js"></script>
         <script type="text/javascript" src="js/main.js"></script> 
    </head>
    <body>
        <div>
            {{ "My GitHub" | markdownify }}
        </div>
        <p>
           ###GitHub Calendar
         </p>
        <div id="github-graph" class="github-graph"></div><!--//github-graph-->
        <p>
            ##    GitHub Activity Stream 
        </p>                 
        <div id="ghfeed" class="ghfeed"></div><!--//ghfeed-->
        <!-- github calendar plugin -->
</body>
</html>
