array-push() ফাংশানের মাধ্যমে কোন এলেমেন্টকে অ্যারের শেষ এলিমেন্ট এ যুক্ত করা হয় । কোন এরের শেষ এ যদি আর কোন এলিমেন্ট লাগে তখন array-push() ব্যাবহার করা হয় । 

উদাহরণঃঃ 
<code>
<html>
   <head>
      <title>JavaScript Array push Method</title>
   </head>
   
   <body>
   
      <script type="text/javascript">
         var numbers = new Array(1, 4, 9);
         
         var length = numbers.push(10);
         document.write("new numbers is : " + numbers ); 
         
         length = numbers.push(20);
         document.write("<br />new numbers is : " + numbers ); 
      </script>
      
   </body>
</html>
</code>

ফলাফলঃঃ 
<code>
new numbers is : 1,4,9,10
new numbers is : 1,4,9,10,20 
</code>
