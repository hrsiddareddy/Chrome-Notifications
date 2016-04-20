## How to enable Chrome Notifications ##

Files needed
1) Manifest.json 
2) Service-Worker.js

Content of Manifest.json
{  
  "name": "Name of your Application",  
  "short_name": "Name of your Application",  
  "icons": [{  
        "src": "images/icon-192x192.png", //Logo Relative path  
        "sizes": "192x192", 
        "type": "image/png" 
      }],  
  "start_url": "/",   
  "display": "standalone",  
  "gcm_sender_id": "Sender Id picked up from Google Developer Console"
}
