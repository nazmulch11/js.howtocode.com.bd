জাভাস্ক্রিপ্ট এ array-pop এর মাধ্যমে এরের শেষের এলিমেন্ট টা আলাদা করার জন্য ব্যবহার করা হয় । 

এটার ব্যাসিক সিনট্যাক্স হচ্ছে <code>array.pop();</code>

উদাহরণঃঃ 

<code>
<html>
   <head>
      <title>JavaScript Array pop Method</title>
   </head>
   
   <body>
   
      <script type="text/javascript">
         var numbers = [1, 4, 9];
         
         var element = numbers.pop();
         document.write("element is : " + element ); 
         
         var element = numbers.pop();
         document.write("<br />element is : " + element );
      </script>
      
   </body>
</html>
</code>

ফলাফলঃঃ 

<code>
element is : 9
element is : 4 
</code>
