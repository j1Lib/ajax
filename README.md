# j1Lib_Ajax
Asynchronous JavaScript and XML ShortHand

The javascript specifies a way to call xhr

###Element


Example:

    j1Lib_ajax(url,function(data){
	  data = data.responseText;
	  alert(data);
    },function(error){
	    
    }).send();
    
###Parameter Reference
- url

- success callback

- fail callback

- method
