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

    <form method="GET" action="mailto:paspanui.hapori@gmail.com" enctype="text/plain">
        <div>Topic</div>
        <input type="text" name="subject" />

        <div>Your Name</div>
        <input name="Name" />

        <div>Your E-Mail</div>
        <input name="E-Mail Address" />

        <div>Feedback / Comment / Suggestion</div>
        <textarea name="Message"></textarea>

        <br/>
        <input type="submit" value="Send" />

        <input type="hidden" name="body" />
    </form>

    <script>
       var form = document.getElementsByTagName('form')[0];
       form.addEventListener('submit',contact,false);
       function contact(e) {
          // Prevent Default Form Submission
          e.preventDefault();

          var target = e.target || e.srcElement;
          var i = 0;
          var message = '';

          // Loop Through All Input Fields
          for(i = 0; i < target.length; ++i) {
             // Check to make sure it's a value. Don't need to include Buttons
             if(target[i].type != 'text' && target[i].type != 'textarea') {
                    // Skip to next input since this one doesn't match our rules
                continue;
             }

             // Add Input Name and value followed by a line break
             message += target[i].name + ': ' + target[i].value + "\r\n";
          }
          // Modify the hidden body input field that is required for the mailto: scheme
          target.elements["body"].value = message;

          // Submit the form since we previously stopped it. May cause recursive loop in some browsers? Should research this.
          this.submit();
       }
    </script>

