# Tech Project Manager test for SMART-TRIBUNE

The test is composed by 3 exercices that are not related. Feel free to do several PR if needed.



## API

The goal to be reached on this exercise is to be able to retrieve 4 questions from the knowledge base as well as their respective official answers and to display them as an accordion list.

Retrieve 4 questions via the endpoint /feedbacks.
For each element, retrieve the most recent linked official comment via the endpoint /comments.
Display all 4 questions' titles in a list.
When you click on the title of a question, display the answer ( "content" field from comment object) as an accordion thanks to https://jqueryui.com/accordion/


### Required information:

* Smart Tribune platformId => 1051
* API Key => aa26a82265190be85fd60522903f4acae43d9a64
* API Secret => b38283155e2226b8b4abe3ef964cd8ab69794ebf


Notes:
* If needed, a PHP wrapper for our API is available on our public Github repo
* API doc => https://www.smart-tribune.com/developers/api?v=v1.1
* To retrieve an official comment, you can pass in "is_official" parameter to true


### Steps to follow for submission:

- [ ] Create a fork of the current repository
- [ ] Commit your code on your fork
- [ ] Open a pull request (PR)


Screenshots:

* TEST API
![api-test-screen](https://user-images.githubusercontent.com/3800117/52867618-9f7e4a80-3141-11e9-92d9-4684be140db2.png)



## Debug Widget - FAQ context

The goal to be reached on this exercise is to be able to find what's going on with the implementation of one of our widgets.
Everything is setup in "debug-widget" folder with a simple html page including our widget.
For now, the widget does not display any question. You need to find and explain what can be the reason(s).

Notes:
* You will find our setup guide here => https://www.smart-tribune.com/developers/setup-guide
* We are talking here about our FAQ context widget

### Explain your exploration

- [ ] How do you check the implementation ?
- [ ] What do you observe ?
- [ ] What could we or the client do to resolve it ?
