.. title: Feedback
.. slug: feedback
.. date: 2019-03-27
.. tags: 
.. category: 
.. link: 
.. description: Provide a feedback form. 
.. type: text
.. hidetitle: True

Feedback
========

Please provide your feedback, comments, or suggestions to the Te Papanui team.

.. raw:: html

    html, body, textarea {
      margin: 0;
      padding: 0;
      border: 0;
      width: 100%;
      height: 100%;
    }
    textarea {
     vertical-align:top;
    }


    <form action="https://formspree.io/f/maylvdvn" method="POST">
 
        <div>Your First Name</div>
        <input type="text" name="First Name" />
        <br/>

        <div>Your Surname</div>
        <input type="text" name="Surname" />
        <br/>

        <div>Your E-Mail</div>
        <input type="email" name="E-Mail Address" />
        <br/>

        <div>Topic</div>
        <input type="text" name="Topic" />
        <br/>
        
        <div>Write your comments and suggestions</div>
        <textarea name="Message"></textarea>

        <br/><br/>

        <button type="submit">Send</button>        
        
    </form>


