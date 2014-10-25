---
layout: post
title:  "How to launch sooner with people powered features"
date:   2014-10-16 10:18:00
---

When you're building an app your first instinct might be to automate everything you can - dont. It's OK to have a few features that aren't fully automated. In the early stages of a product, you don't have a lot of customers or a lot of data. You can _afford_ to do things manually.

Instead of building a feature, you can let the person know that you've received their request and that someone on your team will get back to them in the next hour. Someone on your team gets an email and follows up as soon as possible. I call these "people powered features".

![people powered feature example](/assets/images/articles/peoplepoweredfeature.png)

## Shield yourself from premature optimization

A few common features that could be done manually come to mind: "cancelling a subscription", "removing team members from an account" or "exporting data". Also, there might be features specific to your app that are too expensive to automate initially or perhaps the features aren't part of your core set of features.

> It's not a matter of "if we should build it" - but a matter of "when"

At [Medeo](https://medeohealth.com), an app for people in healthcare to see their patients online, doctors love that their prescriptions are automatically sent to their patient's pharmacy - but you might be surprised to know that we send those prescriptions ourselves. The cost (mostly time) of building a fully automated feature outweighed the cost of doing it manually.

## Start a conversation

This is also a great oppurtunity to open up some dialogue about why the person wanted to use that feature. Ask them why they're removing that team member from their account or what they plan to do with their exported data. Also, you'll learn things you would not normally learn have learnt if the feature was automated from the very beginning. For example I've learned that [something I've learend]

## How to do this yourself

This techni


```
$('*[data-ppf-title').click(function(e){
  e.preventDefault();
  var title = $(this).attr('data-ppf-title');
  var content = $(this).attr('data-ppf-content');

  // Show success message
  swal(title, content, "success");

  /* Send email with Mandrill App
   *
  $.ajax({
    type: “POST”,
    url: “https://mandrillapp.com/api/1.0/messages/send.json”,
    data: {
      ‘key’: ‘YOUR API KEY HERE’,
      ‘message’: {
        ‘from_email’: ‘YOUR@EMAIL.HERE’,
        ‘to’: [
            {
              ‘email’: ‘RECIPIENT_NO_1@EMAIL.HERE’,
              ‘name’: ‘RECIPIENT NAME (OPTIONAL)’,
              ‘type’: ‘to’
            },
            {
              ‘email’: ‘RECIPIENT_NO_2@EMAIL.HERE’,
              ‘name’: ‘ANOTHER RECIPIENT NAME (OPTIONAL)’,
              ‘type’: ‘to’
            }
          ],
        ‘autotext’: ‘true’,
        ‘subject’: ‘YOUR SUBJECT HERE!’,
        ‘html’: ‘YOUR EMAIL CONTENT HERE! YOU CAN USE HTML!’
      }
    }
   }).done(function(response) {
     console.log(response);
   });
  */


});

```