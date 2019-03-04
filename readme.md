# Korean Subtitles for CS231n Spring 2017 
# CS231n 한글번역

Translation project of [CS231n 2017 lecture video](https://www.youtube.com/playlist?list=PLC1qU-LWwrF64f4QKQT-Vg5Wr4qEE1Zxk)  
Also see [CS231n Website](http://cs231n.stanford.edu/)

---------
## Announcements
> CS231n 한글번역 프로젝트입니다. 
  Stanford의 CS231n는 CNN(Convolutional Neural Network)을 중심으로 Deep Learning을 배우는 현존하는 가장 좋은 강의 중 하나. 이 프로젝트는 CS231n을 수강하기에 언어의 장벽으로 힘든 분들을 위한 한글 번역 프로젝트입니다. 많은 분들이 이 강의를 듣고 행복했으면 좋겠습니다. 하지만 CS231n 정도의 수준 그리고 그 이상을 위해서라면 영어실력이 뒷받침해 줘야 하는 것은 명백한 사실입니다.  
> [도올 김용옥 선생의 "영어 수학을 왜 공부해야 하는가?](https://youtu.be/fZk67qnUo3M)
    
    > CS231n에 의 대상
    1) Deep Learning을 처음 접하는 초급자
    2) Deep Learning을 어느정도 알지만 심도깊게 배우고 싶은 중급자
    3) Deep Learning의 트렌드를 살펴 보고자 하는 상급자 

    > 자세한 Prerequisites은 Lecture 1을 참고하시기 바랍니다. 
    
    많은 분들의 관심과 격려로 힘내고 있습니다. 감사합니다 :D
    그리고 또한 많은 분들께서 오역, 오타관련 Issues, Pull requests, Email 등을 
    보내주시고 계십니다. 특히 오타 찾는게 정말 힘든데 이렇게 도와주시니 정말 감사할 따릅입니다 :D 

    현재 draft 버전은 오역, 오타, 싱크 등 문제가 많습니다. 
    오역, 오타, 싱크 문제는 지속적으로 업데이트하고 있으며, first revision을 작업중입니다. 
    first revision이 draft버전보다 많이 개선된 버전이므로 참고해주시기 바랍니다. 
    다시 한번 모두에게 감사드립니다 XD

----------
## Instructors
    Fei-Fei Li: http://vision.stanford.edu/feifeili/  
    Justin Johnson: http://cs.stanford.edu/people/jcjohns/  
    Serena Yeung: http://ai.stanford.edu/~syyeung/  

----------
## Prerequisites
    Any video player with codecs which might be let you watch lectures
        Recommendation
            Windows : PotPlayer(kakao)
            Linux   : SM Player
            IOS     : Whatever you can :(

----------
## Usage

1. You should download lectures from youtube
    - You need a video downloader like [4k video downloader](https://www.4kdownload.com/ko/products/product-videodownloader) (maybe support most of platforms like Windows, Linux(Ubuntu), MacOS)
    - Download this [Youtube Playlist](https://www.youtube.com/playlist?list=PLC1qU-LWwrF64f4QKQT-Vg5Wr4qEE1Zxk) with downloader
    - If you take "4k video downloader", you can download whole lectures "at once" not "each", with Playlist.      
    
2. and Enjoy videos with Subtitles  

        root
        └── eng
            └── Subtitles in English.
        └── kor 
            └── Subtitles in Korean.

----------

## Update Note
    Welcome to Pull Request

    1. Update News
    ...
    2018.05.23 - Complete Lecture 6(draft)
    2018.06.14 - Complete Lecture 7(draft)
    2018 06 26 - Complete Lecture 8(draft) 
    2018 07 27 - Complete Lecture 1(1st Revision) 
    2018 07 09 - Complete Lecture 9(draft) 
    2018 07 16 - Complete Lecture 2(1st Revision) 
    2018 07 30 - Complete Lecture 10(draft) 
    2018 08 13 - Complete Lecture 11(draft) 
    2018 09 24 - Complete Lecture 12(draft)
    2018 10 06 - Complete Lecture 13(draft)
    2018 12 31 - Complete Lecture 14(draft)

    1. Milestone
    Lecture 01 : Complete(draft + 1st Revision) 
    Lecture 02 : Complete(draft + 1st Revision)
    Lecture 03 : Complete(draft)
    Lecture 04 : Complete(draft)
    Lecture 05 : Complete(draft)
    Lecture 06 : Complete(draft)
    Lecture 07 : Complete(draft)
    Lecture 08 : Complete(draft)
    Lecture 09 : Complete(draft)
    Lecture 10 : Complete(draft)
    Lecture 11 : Complete(draft)
    Lecture 12 : Complete(draft)
    Lecture 13 : Complete(draft)
    Lecture 14 : Complete(draft)
    Invited Talk 1 : not yet :(
    Invited Talk 2 : not yet :(
----------
## Table of Contents (CS231n 2017)


 Please see also
1. Detailed syllabus 
 [[2016]](http://cs231n.stanford.edu/2016/syllabus.html)
 [[2017]](http://cs231n.stanford.edu/2017/syllabus.html)
 [[2018]](http://cs231n.stanford.edu/syllabus.html)

2. Lecture Vodeos Playlist
[[2016]](https://www.youtube.com/playlist?list=PLkt2uSq6rBVctENoVBg1TpCC7OQi31AlC)
[[2017]](https://www.youtube.com/playlist?list=PLC1qU-LWwrF64f4QKQT-Vg5Wr4qEE1Zxk) 
[2018 is not in public] 


#### Status info
| *Status info* | Symbol  |*Status info*   |Symbol                           |
|:-------------:|:-------:|:--------------:|:-------------------------------:|
|**Draft**      |:pencil2:|**1st_revision**|:pencil2: :scissors:             |
|**not yet**    |:no_bell:|**2nd_revision**|:pencil2: :scissors: :scissors:  |


----

| Event Type  | Description       |Videos(youtube)      |Slides      | Subtitles| Status |
|:--------:|:-----------------:|:-----------:|:--------:|:--------:|:----:|
|Lecture 1        |Introduction to Convolutional Neural Networks for Visual Recognition|[video](https://www.youtube.com/watch?v=vT1JzLTH4G4&t=0s&index=1&list=PLC1qU-LWwrF64f4QKQT-Vg5Wr4qEE1Zxk)|[slide](http://cs231n.stanford.edu/slides/2017/cs231n_2017_lecture1.pdf)|[english](https://github.com/insurgent92/cs231n_spring_2017/blob/master/eng/Lecture%201%20_%20Introduction%20to%20Convolutional%20Neural%20Networks%20for%20Visual%20Recognition.srt)<p>[korean](https://github.com/insurgent92/CS231N_17_KOR_SUB/blob/master/kor/Lecture%201%20%20%20Introduction%20to%20Convolutional%20Neural%20Networks%20for%20Visual%20Recognition.ko.srt)|:pencil2: :scissors:|
| Lecture 2        |Image Classification|[video](https://www.youtube.com/watch?v=OoUX-nOEjG0&list=PLC1qU-LWwrF64f4QKQT-Vg5Wr4qEE1Zxk&index=1)|[slide](http://cs231n.stanford.edu/slides/2017/cs231n_2017_lecture2.pdf)|[english](https://github.com/insurgent92/cs231n_spring_2017/blob/master/eng/Lecture%202%20_%20Image%20Classification.srt)<p>[korean](https://github.com/insurgent92/CS231N_17_KOR_SUB/blob/master/kor/Lecture%202%20%20%20Image%20Classification.ko.srt)|:pencil2: :scissors:|
| Lecture 3        |Loss Functions and Optimization|[video](https://www.youtube.com/watch?v=h7iBpEHGVNc&index=2&list=PLC1qU-LWwrF64f4QKQT-Vg5Wr4qEE1Zxk)|[slide](http://cs231n.stanford.edu/slides/2017/cs231n_2017_lecture3.pdf)|[english](https://github.com/insurgent92/cs231n_spring_2017/blob/master/eng/Lecture%203%20_%20Loss%20Functions%20and%20Optimization.srt)<p>[korean](https://github.com/insurgent92/CS231N_17_KOR_SUB/blob/master/kor/Lecture%203%20%20%20Loss%20Functions%20and%20Optimization.ko.srt)|:pencil2: |
| Lecture 4        |Introduction to Neural Networks|[video](https://www.youtube.com/watch?v=d14TUNcbn1k&index=3&list=PLC1qU-LWwrF64f4QKQT-Vg5Wr4qEE1Zxk)|[slide](http://cs231n.stanford.edu/slides/2017/cs231n_2017_lecture4.pdf)|[english](https://github.com/insurgent92/cs231n_spring_2017/blob/master/eng/Lecture%204%20_%20Introduction%20to%20Neural%20Networks.srt)<p>[korean](https://github.com/insurgent92/CS231N_17_KOR_SUB/blob/master/kor/Lecture%204%20%20%20Introduction%20to%20Neural%20Networks.ko.srt)|:pencil2: |
| Lecture 5        |Convolutional Neural Networks|[video](https://www.youtube.com/watch?v=bNb2fEVKeEo&list=PLC1qU-LWwrF64f4QKQT-Vg5Wr4qEE1Zxk&index=4)|[slide](http://cs231n.stanford.edu/slides/2017/cs231n_2017_lecture5.pdf)|[english](https://github.com/insurgent92/cs231n_spring_2017/blob/master/eng/Lecture%205%20_%20Convolutional%20Neural%20Networks.srt)<p>[korean](https://github.com/insurgent92/CS231N_17_KOR_SUB/blob/master/kor/Lecture%205%20%20%20Convolutional%20Neural%20Networks.ko.srt)|:pencil2: |
| Lecture 6        |Training Neural Networks I|[video](https://www.youtube.com/watch?v=wEoyxE0GP2M&index=5&list=PLC1qU-LWwrF64f4QKQT-Vg5Wr4qEE1Zxk)|[slide](http://cs231n.stanford.edu/slides/2017/cs231n_2017_lecture6.pdf)|[english](https://github.com/insurgent92/cs231n_spring_2017/blob/master/eng/Lecture%206%20_%20Training%20Neural%20Networks%20I.srt)<p>[korean](https://github.com/insurgent92/CS231N_17_KOR_SUB/blob/master/kor/Lecture%206%20%20%20Training%20Neural%20Networks%20I.ko.srt)|:pencil2: |
| Lecture 7        |Training Neural Networks II|[video](https://www.youtube.com/watch?v=_JB0AO7QxSA&list=PLC1qU-LWwrF64f4QKQT-Vg5Wr4qEE1Zxk&index=6)|[slide](http://cs231n.stanford.edu/slides/2017/cs231n_2017_lecture7.pdf)|[english](https://github.com/insurgent92/cs231n_spring_2017/blob/master/eng/Lecture%207%20_%20Training%20Neural%20Networks%20II.srt)<p>[korean](https://github.com/insurgent92/CS231N_17_KOR_SUB/blob/master/kor/Lecture%207%20%20%20Training%20Neural%20Networks%20II.ko.srt)|:pencil2: |
| Lecture 8        |Deep Learning Software|[video](https://www.youtube.com/watch?v=6SlgtELqOWc&list=PLC1qU-LWwrF64f4QKQT-Vg5Wr4qEE1Zxk&index=7)|[slide](http://cs231n.stanford.edu/slides/2017/cs231n_2017_lecture8.pdf)|[english](https://github.com/insurgent92/cs231n_spring_2017/blob/master/eng/Lecture%208%20_%20Deep%20Learning%20Software.srt)<p>[korean](https://github.com/insurgent92/CS231N_17_KOR_SUB/blob/master/kor/Lecture%208%20%20%20Deep%20Learning%20Software.ko.srt)|:pencil2: |
| Lecture 9        |CNN Architectures|[video](https://www.youtube.com/watch?v=DAOcjicFr1Y&index=8&list=PLC1qU-LWwrF64f4QKQT-Vg5Wr4qEE1Zxk)|[slide](http://cs231n.stanford.edu/slides/2017/cs231n_2017_lecture9.pdf)|[english](https://github.com/insurgent92/cs231n_spring_2017/blob/master/eng/Lecture%209%20_%20CNN%20Architectures.srt)<p>[korean](https://github.com/insurgent92/CS231N_17_KOR_SUB/blob/master/kor/Lecture%209%20%20%20CNN%20Architectures.ko.srt)|:pencil2: |
| Lecture 10       |Recurrent Neural Networks|[video](https://www.youtube.com/watch?v=6niqTuYFZLQ&list=PLC1qU-LWwrF64f4QKQT-Vg5Wr4qEE1Zxk&index=9)|[slide](http://cs231n.stanford.edu/slides/2017/cs231n_2017_lecture10.pdf)|[english](https://github.com/insurgent92/cs231n_spring_2017/blob/master/eng/Lecture%2010%20_%20Recurrent%20Neural%20Networks.srt)<p>[korean](https://github.com/insurgent92/CS231N_17_KOR_SUB/blob/master/kor/Lecture%2010%20%20%20Recurrent%20Neural%20Networks.ko.srt)|:pencil2: |
| Lecture 11       |Detection and Segmentation|[video](https://www.youtube.com/watch?v=nDPWywWRIRo&index=10&list=PLC1qU-LWwrF64f4QKQT-Vg5Wr4qEE1Zxk)|[slide](http://cs231n.stanford.edu/slides/2017/cs231n_2017_lecture11.pdf)|[english](https://github.com/insurgent92/cs231n_spring_2017/blob/master/eng/Lecture%2011%20_%20Detection%20and%20Segmentation.srt)<p>[korean](https://github.com/insurgent92/CS231N_17_KOR_SUB/blob/master/kor/Lecture%2011%20%20%20Detection%20and%20Segmentation.ko.srt)|:pencil2: |
| Lecture 12       | Visualizing and Understanding|[video](https://www.youtube.com/watch?v=6wcs6szJWMY&index=11&list=PLC1qU-LWwrF64f4QKQT-Vg5Wr4qEE1Zxk)|[slide](http://cs231n.stanford.edu/slides/2017/cs231n_2017_lecture12.pdf)|[english](https://github.com/insurgent92/cs231n_spring_2017/blob/master/eng/Lecture%2012%20_%20Visualizing%20and%20Understanding.srt)<p>[korean](https://github.com/insurgent92/CS231N_17_KOR_SUB/blob/master/kor/Lecture%2012%20%20%20Visualizing%20and%20Understanding.ko.srt)|:pencil2: |
| Lecture 13       |Generative Models|[video](https://www.youtube.com/watch?v=5WoItGTWV54&list=PLC1qU-LWwrF64f4QKQT-Vg5Wr4qEE1Zxk&index=12)|[slide](http://cs231n.stanford.edu/slides/2017/cs231n_2017_lecture13.pdf)|[english](https://github.com/insurgent92/cs231n_spring_2017/blob/master/eng/Lecture%2013%20_%20Generative%20Models.srt)<p>[korean](https://github.com/insurgent92/CS231N_17_KOR_SUB/blob/master/kor/Lecture%2013%20%20%20Generative%20Models.ko.srt)|:pencil2:|
| Lecture 14       |Deep Reinforcement Learning|[video](https://www.youtube.com/watch?v=lvoHnicueoE&index=13&list=PLC1qU-LWwrF64f4QKQT-Vg5Wr4qEE1Zxk)|[slide](http://cs231n.stanford.edu/slides/2017/cs231n_2017_lecture14.pdf)|[english](https://github.com/insurgent92/cs231n_spring_2017/blob/master/eng/Lecture%2014%20_%20Deep%20Reinforcement%20Learning.srt)<p>[korean](https://github.com/insurgent92/CS231N_17_KOR_SUB/blob/master/kor/Lecture%2014%20%20%20Deep%20Reinforcement%20Learning.ko.srt)|:pencil2:|
| Guest Lecture       |Invited Talk: [Song Han](https://songhan.mit.edu/) <br> Efficient Methods and Hardware for Deep Learning|[video](https://www.youtube.com/watch?v=eZdOkDtYMoo&index=14&list=PLC1qU-LWwrF64f4QKQT-Vg5Wr4qEE1Zxk)|[slide](http://cs231n.stanford.edu/slides/2017/cs231n_2017_lecture15.pdf)|[english](https://github.com/insurgent92/cs231n_spring_2017/blob/master/eng/Lecture%2015%20_%20Efficient%20Methods%20and%20Hardware%20for%20Deep%20Learning.srt)<p>[korean]|:no_bell:|
| Guest Lecture       |Invited Talk: [Ian Goodfellow](http://www.iangoodfellow.com/) <br> Adversarial Examples and Adversarial Training|[video](https://www.youtube.com/watch?v=CIfsB_EYsVI&list=PLC1qU-LWwrF64f4QKQT-Vg5Wr4qEE1Zxk&index=15)|[slide](http://cs231n.stanford.edu/slides/2017/cs231n_2017_lecture16.pdf)|[english](https://github.com/insurgent92/cs231n_spring_2017/blob/master/eng/Lecture%2016%20_%20Adversarial%20Examples%20and%20Adversarial%20Training.srt)<p>[korean]|:no_bell:|




----------
## Screenshot

![alt_tag](samples.png)

----------
## Contributors
- Jaewon Lee (Image Processing & Computer Vision Lab, KNU)
- Azure (Image Processing & Computer Vision Lab, KNU)
----------

## LICENSE
MIT
