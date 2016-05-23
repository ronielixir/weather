# weather

DOM
           html
            |
     +- - - +- - - - - - - - - - -+
     |                            |
    head                         body
     |                            |
     |              + - - - - - - + - -+ - - - - - +
 +---++----+       div (.main)        proc        proc
 |    |    |        |                jQuery       Your
link link link     div (.container)             script.js
-google-Css-font    |
-bootstrap.css     div (.row)
-your               |
  style.css        div (.col-sm-5 .col-offset-7)
                    |
          + - - -+ -+ -+
          |      |     |
          h1     h2   div (.forecast)
                       |
 + - - -+ . . . . + - -+-+ . . . . + - - -+ . . . . + - - -+ . . . . + - - -+ 
div    div       div    div       div    div       div    div       div    div  
(.day  (.hourly  (.day  (.hourly  (.day  (.hourly  (.day  (.hourly  (.day  (.hourly  
 .row)  .row)     .row)  .row)     .row)  .row)     .row)  .row)     .row)  .row)

                                         div (.day
                                         |   .row)
                                         |
   +- - - - - - - - - + - - - - - - -+ - + - - - - - + - - - - - - -+
  div(.weekday       div(.weather   div(.weather    div(.high     div(.low
   |  .col-xs-4       |  .col-xs-3)     .col-xs-1)   |  .col-xs-2) |  .col-xs-2)
 + + - - - - - - -+  img                             p             p
 |                |
span              p
(.glyphicon-plus)
       

        div(.hourly
        |  .row)
+ - - - + - - - 4x ->->->
|               |
div            div(.col-xs-2)
 .col-xs-4      |
                |
          + - - + - -+ - +
          |          |   |
          p(.hour)   p   p(.temp)
                     |
                    img
