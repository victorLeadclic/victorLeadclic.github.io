<!DOCTYPE html>
<html lang="en">
  <head>
  <style>
    .slds-visual-picker_vertical .slds-visual-picker__figure {
      height: inherit !important;
    }

     .runtime_appointmentbookingFlowLocation .slds-visual-picker_vertical {
        display: inline-flex !important;
      }
  </style>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>FORM DRUNI</title>
    <link rel="stylesheet" href="./style.css">
    <link rel="icon" href="./favicon.ico" type="image/x-icon">
	<script src="https://druni--int.sandbox.lightning.force.com/lightning/lightning.out.js"></script>
  	<script>
    $Lightning.use("runtime_appointmentbooking:lightningOutGuest",

    function() { // Callback once framework and app load
    
    $Lightning.createComponent(
    
    "lightning:flow", // top-level component of your app
    
    { }, // attributes to set on the component when created
    
    "contenedorFlujo", // the DOM location to insert the component
    
    function(component) { // API name of the Flow
     component.startFlow("Case_Screen_CasoFormularioWeb");
    
    }
    
    );
    
    }, 'https://druni--int.sandbox.lightning.force.com'
    );

  </script>
  </head>
  <body>
    <main>
      <div id="contenedorFlujo"></div>
      <p>HELLO</p>
    </main>
  </body>
</html>
