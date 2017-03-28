<!DOCTYPE html>
<html>
  <head>
    <style>
      #map {
        width: 100%;
        height: 100%;
        
        background-color: black;
      }
      html, body {
      height:100%
      margin:0
      padding:0
    </style>
  </head>
  <body>
    <h3>Allegheny County Concentrated Heroin Deaths in 2016</h3>
    <div id="map"></div>
 <script>
      function initMap() {
      
        var map = new google.maps.Map(document.getElementById('map'), {
          zoom: 10,
          center: {lat: 40.4406, lng: 79.9959};
          var labels= 'ABCDEFGHIJKLMNOPQRSTUVWXYZ123456789!@%$'
        });
Var locations = [
[lat:40.5228382, lng:-79.8324755]
[lat:40.4720642, lng:-79.8324755]
[lat:40.5228382, lng:-79.8324755]
[lat:40.5228382,lng:-79.9024779]
[lat:40.4509149,lng:-79.9136731]
[lat:40.4720642,lng:-79.8436796]
[lat:40.6194238,lng:-79.9789606]
[lat:40.3380768,lng:-80.0171609]
[lat:40.4331995,lng:-80.0171609]
[lat:39.9568094,lng:-79.9528451]
[lat:40.6315486,lng:-124.0571857]
[lat:46.8627802,lng:-80.0870155]
[lat:40.3205701,lng:-79.9556424]
[lat:40.4379259,lng:-79.9024779]
[lat:40.4004712,lng:-79.8604831]
[lat:40.4043414,lng:-79.9080756]
[lat:40.3050009,lng:-79.4872619]
[lat:40.5244467,lng:-79.8884819]
[lat:40.3260206,lng:-79.8436796]
[lat:40.6194238,lng:-80.3547286]
[lat:40.7664977,lng:-79.9696277]
[lat:40.3760655,lng:-86.004313]
[lat:39.9568094,lng:-80.0479039]
[lat:40.3727711,lng:-79.8184684]
[lat:40.4989334,lng:-79.9556424]
[lat:40.4379259,lng:-80.1149414]
[lat:40.4693953,lng:-80.1149414]
[lat:40.4693953,lng:-80.0367259]
[lat:40.4828051,lng:-79.8604831]
[lat:40.4043414,lng:-80.0171609]
[lat:40.4331995,lng:-80.1372757]
[lat:40.3400563,lng:-79.9136731]
[lat:40.3509675,lng:-79.8016569]
[lat:40.3713759,lng:-80.0143656]
[lat:40.3900597,lng:-79.9696277]
[lat:40.497124,lng:-79.8016569]
[lat:40.3713759,lng:-79.9919995]
[lat:40.4083044,lng:-79.9696277]
[lat:40.3760655,lng:-80.1149414]
[lat:40.4088514,lng:-79.8492812]
[lat:40.3730698,lng:-79.9612368]

     }  </script>
    <script async defer
    src="https://maps.googleapis.com/maps/api/js?key=AIzaSyCN-5toCtamubAGqQFsfcpAh5cHKa-goY8&callback=initMap">
    </script>
    function initMap() {
  var map = new google.maps.Map(document.getElementById('map'), {
    zoom: 4,
    center: {lat:40.4083 , lng: 79.9920}  
  });
#circle around area with most deaths in 2016/#
  var marker = new google.maps.Marker({
    position: map.getCenter(),
    icon: {
      path: google.maps.SymbolPath.CIRCLE,
      scale: 5
    },
    draggable: true,
    map: map
  });
} 
 </body>
</html>
<head>Other Drug Deaths In Allegheny County</head>
 <script type="text/javascript" src="https://www.gstatic.com/charts/loader.js"></script>
  <script>
    google.charts.load('current', { 'packages': ['map'] });
    google.charts.setOnLoadCallback(drawMap);

    function drawMap() {
      var data = google.visualization.arrayToDataTable([
        ['Drug', 'Number of Deaths(2008-2016)'],
        ['Heroin', 'Heroin: 1467'],
        ['Ethanol', 'Ethanol: 922'],
        ['Cocaine', 'Cocaine: 863'],
        ['Fentanyl', 'Fentanyl: 597'],
        ['Alprazolam', 'Alprazolam: 486'],
        ['Oxycodone', 'Oxycodone: 379'],

      ]);

    var options = {
      showTooltip: true,
      showInfoWindow: true
    };

    var map = new google.visualization.Map(document.getElementById('chart_div'));

    map.draw(data, options);
  };
  </script>
  </head>
  <body>
    <div id="chart_div"></div>
  </body>
  
  Deciding what to create my second synthesis on was not terribly difficult as I knew I wanted to create a visual of something that has been increasingly detrimental to the city of Pittsburgh for years now, the heroin epidemic. 
  While I worked through the process of creating my second site I had a vision of how I felt it should appear but could not quite figure out how to make it come together as though I had visioned it in my head.
  I wanted a plain background that was not too dull looking, as it could make the viewer disinterested in the site as a whole, but also not too distracting since so it would take away from the focal point, the graphics. 
  Since I felt my map and bar chart portrayed information that should be known by a more widespread audience within Pittsburgh I decided using a plain black background would be the cleanest, most non-distracting look in order to highlight the information to it's fullest potential. 
  I imagined the site to be very simple and for it to have minimally needed navigation because what I felt was the most important was not how the site looked, but the information that was contained within the site. 
  I wanted people to open this page and to instantly be met with the harsh reality of heroin related deaths in Pittsburgh and how that compares in regards to other commonly abused drugs such as alcohol, cocaine, and opiates also in the Pittsburgh area.
  I expect my audience to be somewhat in a state of shock with how close to home heroin abuse truly is and for some individuals living in more affluent suburbs around the Pittsburgh area to realize that this epidemic is not secluded to the city and its immediate neighboring areas, but in fact it reaches
  all areas around the city of Pittsburgh, even the richest. To do this and create this effect I felt the black background was the best color scheme. Though the color was important what I thought would cause the greatest impact was using the very relatable Google maps within the site to portray the deaths caused by heroin.
  Using the navigation type look that Google maps gives to the page takes something not everyone knows much about (heroin) and puts it within a platform everyone uses regardless of age, socio-economic status, or geographical location. Creating this page was obviously done for an assignment but the data contained within the
  page hits close to home as I have had multiple friends in the Pittsburgh area whose siblings or close relatives have fallen victim to the heroin epidemic. Watching this drug leave everlasting negative impacts on some of those whom I look at as family has definitely taken a toll on me both mentally and emotionally and has effectively 
  changed my outlook on many things. As I complete this work I can look back on it and realize the simplicity of it could potentially create a lasting impression on someone who views it. The heroin epidemic within, and around Pittsburgh has steadily been on the rise for several years and if even something as miniscule as this could make
  a difference I feel it should be done. 
  
  
  
  <body>
  </html>
