#JavaScript Performance CheatSheet

 - $().eq(0) => $().first() => $(":first")

 - $(":not(...)") => $().not("...")
 
 - for( var i=0, l=array.length; i<l; i+=1 )
 
 - $( document.getElementById("...") ) => $( "#..." )
 
 - $().get(0).innerHTML = "..." => $().html("...")
 
 - $().get(0).removeChild => $().remove()
 
 - for(var key in Object){Object[key]} => $.each(Object,function(){})
