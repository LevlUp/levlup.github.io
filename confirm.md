---
layout: page
custom_css: sweetalert
custom_js: sweetalert
---
$(document).ready(function() {
swal({ 
  title: "Thanks",
   text: "I'll get back to you ASAP",
    imageUrl: "/img/thumbs-up.jpg" 
  },
  function(){
    window.location.href = '';
});