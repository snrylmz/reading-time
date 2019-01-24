# Reading Time
Article reading time calculation with jquery


## Description
Based on an article at medium.com, I created a simple formula such as 
reading time (in seconds) / number of words, and according to the result, 
the reading time of a word is 0.2857563851 seconds.

<strong>#readed-words</strong> to find the number of words by finding the gaps.

The total number of words * The word reading time gives us the result in seconds,
by making an account. Then we turn it into minutes by making / 60.

---



```javascript


$(function() {
    var text = $('#readed-words').text();
    var wordsCount = text.split(' ').length;
    var wordTime = 0.2857563851;
    var readingTime = Math.round(wordTime * wordsCount / 60);
      $('#output').html('Number of words : ' + wordsCount + '</br> Reading Time: ☕️' + readingTime + ' Minutes reading time');
  });
```

---

It works even if it's not very strong.

----sorry for the translation.

## Getting Started

To begin using this template, choose one of the following options to get started:
* Clone the repo: `git clone https://github.com/snrylmz/reading-time.git`





## Creator

Reading Time was created by and is maintained by **[Şener YILMAZ](http://senerov.com/)**

* https://twitter.com/senerovii
* https://gitlab.com/senerovv
* https://github.com/snrylmz


## Copyright and License

 Code released under the [MIT] license.
 
