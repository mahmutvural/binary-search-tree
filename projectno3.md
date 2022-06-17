# Patika.dev <a href="https://app.patika.dev/beyazbaret"> profilim
  <pre> <b> <h2> Proje 3- Binary Search Tree Projesi </h2> </b>
  <em> "[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız." </em> <p>
 
  [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary Search Tree aşamaları
  
  <b> 1. Aşama:</b> Root 7 seçilir. 5 değeri 7 değerinden küçük olduğu için sol tarafa yazılır.   
  
            7
          /  
         5    
         
   <b> 2. Aşama:</b> 1 değeri 7 değerinden küçük olduğu için sol tarafa gidilir. 5 değerinden de küçük olduğu için 5 in soluna yazılr.   
              
          7
        /    
       5        
      /       
     1    
      
    <b> 3. Aşama:</b> 8 değeri 7 değerinden büyük olduğu için sağ tarafa yazılır. 
         
          7
        /    \ 
       5      8  
      /       
     1 
     
    <b> 4. Aşama:</b> 3 değeri 7 den ve 5 den küçük 1 den büyük olduğu için 1 in sağ tarafa yazılır. 
         
          7
        /    \ 
       5      8  
      /        
     1   
      \
       3
       
     <b> 5. Aşama:</b> 6 değeri 7 den küçük 5 den büyük olduğu için 5 ün sağına yazılır. 
         
          7
        /    \ 
       5      8  
      / \      
     1   6
      \
       3
       
     <b> 5. Aşama:</b> 0 değeri 7 den, 5 den ve 1 den küçük olduğu için 1 in soluna yazılır. 
         
          7
        /    \ 
       5      8  
      / \      
     1   6
    / \
   0   3 

     <b> 6. Aşama:</b> 9 değeri 7 den ve 8 den büyük olduğu için 8 in sağına yazılır. 
         
          7
        /    \ 
       5      8  
      / \      \
     1   6      9
    / \
   0   3  
     
      <b> 7. Aşama:</b> 4 değeri 7 den,5 den küçük 1 den ve 3 den büyük olduğu için 3 ün sağına yazılır. 
        
          7
        /    \ 
       5      8  
      / \      \
     1   6      9
    / \
   0   3   
        \
         4
         
      <b> 8. Aşama:</b> 2 değeri 7 den ve 5 den küçük, 1 den büyük, 3 den küçük olduğu için 3 ün soluna yazılır. 
                   
          7
        /    \ 
       5      8  
      / \      \
     1   6      9
    / \
   0   3   
      / \
     2   4     
 </pre>
