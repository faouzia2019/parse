<!DOCTYPE html>
<html>
<head>
<title>Test APPLICATION</title>
</head>
<body>

<h1>BIENVENUE</h1>

    
  <script type="text/javascript" src="node_modules\parse\dist\parse.min.js"></script>
     <script type="text/javascript" >

Parse.serverURL = 'https://parseapi.back4app.com'; // This is your Server URL
Parse.initialize(
  'i92c77pZLsEnwZrIK5mqt6WGPdoQ4KZAh2IkSppO', // This is your Application ID
  'HOskuAWUex1Ln6mhhzIy1i2xFPo75hf84Q1Xxs2M' // This is your Javascript key
);
         var persone =Parse.Object.extend("person");
         var persone =new(persone);
         persone.set("name","bayrem");
         persone.set("age",10);
         persone.save();
</script>
</body>
</html>
