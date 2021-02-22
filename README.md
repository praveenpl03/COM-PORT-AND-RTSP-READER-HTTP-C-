# COM-PORT-AND-RTSP-READER FROM PC To Server
Reading COM Port Values and RTSP Snapshots to HTTP Server
You can get 
Com Port Readings on http://127.0.0.1:8000
RTSP Screen Shots on http://127.0.0.1:8001

This can be used emberd data to websites from local computers and can be pushed to server for further processing.
http cross orgin is allowed on c# program 
u need to add crossorgin on image tag 

Using ajax 
For RTSP Snapshot


document.getElementById("snap").setAttribute(
        'src',"http://127.0.0.1:8001/snapshot.jpg");
        
        
 For Weight from COMPORT   
 
 
 function lockWeight(){
         jQuery.support.cors = true;
          $.ajax({url: "http://127.0.0.1:8000/", success:   function(result){

if (parseInt(result) > 0){
  $('#saver').prop("disabled",false);
      $("#weight").html(result);
     $("#weight_com").val(result);
}
 else if(parseInt(result) ==0)
             {
             $('#saver').prop("disabled",true);
             $("#weight").html("0");
              }
              
  }});


}


You can contact me for any assistance if needed . 8547861657 / praveen.pl03@gmail.com
