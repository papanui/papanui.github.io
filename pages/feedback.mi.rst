.. title: Feedback
.. slug: feedback
.. date: 2019-03-27
.. tags: 
.. category: 
.. link: 
.. description: Maori Provide a feedback form. 
.. type: text
.. hidetitle: True

Urupare
========

Tena koa whakahoki mai o urupare, korero, whakaaro ranei ki te tiima o Te Papanui.

.. raw:: html
    
    <!-- Add CSS for textarea to increase width -->
    <style>
        textarea {
          width: 80%;
          }
    </style>    
        
    <form action="https://formspree.io/f/maylvdvn" method="POST">

        <!-- Your First Name --> 
        <div>To Ingoa Tuatahi (hiahiatia)</div>
        <input type="text" name="First Name" required/>
        <br/>

        <!-- Your Surname -->
        <div>To Ingoa (hiahiatia)</div>
        <input type="text" name="Surname" required/>
        <br/>

        <!-- Your E-Mail -->
        <div>To Imera-Imeera (hiahiatia)</div>
        <input type="email" name="E-Mail Address" required/>
        <br/>

        <!-- Topic -->
        <div>Kaupapa korero</div>
        <input type="text" name="Topic" />
        <br/>
        
        <!-- If rows and cols are not used then use CSS width and height 
            rows="4" cols="100"-->
        <!-- Write your comments and suggestions -->
        <div>Tuhia o korero me o whakaaro</div>
        <textarea name="Message"></textarea>

        <br/><br/>

        <!-- Send -->
        <button type="submit">Tukuna</button>        
        
    </form>

 

