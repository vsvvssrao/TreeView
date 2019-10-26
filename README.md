# TreeView

A JQuery Plugin for Tree View with Lazy loading capability

  

# USAGE

  
  
# Client side code
```markdown
<!DOCTYPE  html>
<html>
<head>
----
----
<link  rel="stylesheet"  href="css/tree.css">
<script  src="https://ajax.googleapis.com/ajax/libs/jquery/3.4.1/jquery.min.js"></script>
---
---
</head>
<body>
-----
<div  id="myListTree"></div>
----
<script  src="tree.js"></script>
<script>
$('#myListTree').tree({
data:  function(){
return  JSONData
},
onDemandData:  function () {
return  JSONData
}
});
</script>
</body>
</html>

  

```

# JSON Data Structure
```
var  Treedata  = {
"result": [{
"id":  "l01",
"displayName":  "Beverages",
"hasChild":  true,
"isLoaded":  true,
"children": [{ }] /* Child will also follow the same structure */
}


```
