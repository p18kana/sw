<h1 align= left> Τεχνολογία Λογισμικού: </h1> 

<h3 align= left>  Θεοχάρης Παναγιώτης Χαραλαμπίδης && ΑΜ : Π2018127 </h3>

[<img src="https://raw.githubusercontent.com/runtheorun-exe/swfiles/main/gh-pride.png" width="50"/>](https://github.com/runtheorun-exe)   [<img src="https://raw.githubusercontent.com/runtheorun-exe/swfiles/main/mailto.png" width="50"/>](mailto:p18char@ionio.gr)



| Εβδομάδα* | Παραδοτέο |  Βίντεο |
| --- | --- | --- |
| 1 | [Intro](#intro) | Υποβολή μέσω της εφαρμογής |
| 2 | [The CV](#cv) | Υποβολή μέσω της εφαρμογής |
| 3 | [Ionian University Site PR](#pull-request-1) | [Answered Here](#week-3) |
| 4 | [CLI Exercise #1](#cli-exercise-1) | Υποβολή μέσω εφαρμογής
| 5 | [Collaborative Work #1](#collaborative-work-pibook-1) | Υποβολή μέσω εφαρμογής
| 6 | [CLI Exercise #2](#cli-exercise-2) | [Answered Here](#week-6)
| 7 | [CV pt2](#cv-part-2) | [Answered Here](#week-7)
| 8 | ~~Αίτημα ενσωμάτωσης στην ιστοσελίδα~~ |  [Answered Here](#week-8)
| 9 | [CLI Exercise #3](#cli-exercise-3) | [Answered Here](#week-9)
| 10 | [Collaborative Work #2](#collaborative-work-pibook-2) | [Answered Here](#week-9)
| 11 | [CLI Exercise #4](#cli-exercise-4) | null | 
| 12 | [Epilogue](#epilogue) | null |

### Intro
Σύντομη Περιγραφή:
Κύκλος ζωής λογισμικού. Μεθοδολογίες ανάπτυξης λογισμικού. Σχεδιασμός και αρχιτεκτονική συστήματος. Κατασκευή διεπαφής χρήστη. Διαδικασία παράδοσης και συντήρησης συστημάτων λογισμικού. Συνεργατικά συστήματα. Ψυχαγωγικό και Εκπαιδευτικό Λογισμικό.
Αντικειμενικοί Στόχοι - Επιδιωκόμενα Μαθησιακά Αποτελέσματα:

  Με την επιτυχή ολοκλήρωση του μαθήματος ευελπιστώ να είμαι σε θέση να:
      Κάνω συλλογή και ανάλυση δεδομένων για την κατασκευή λογισμικού.
      Κάνω σχεδίαση και κατασκευή λογισμικού(με βάση τις γνώσεις που σύλλεξα ;) στο μάθημα HCI.
      Συνεργάζομαι σε ομάδα για την ανάπτυξη και συντήρηση λογισμικού.
        
Στόχοι φοιτητή: Ευελιξία στη χρήση Git/Github και παρελκόμενων εργαλείων

### Παραδοτέα

## CV:
The CV website can be found [here](https://runtheorun-exe.github.io/online-cv/) and its repo [here](https://github.com/runtheorun-exe/online-cv).
Currently it is static, and hosted by gh-pages. It is "dressed" by a modified skin provided by the cv [template](https://github.com/sharu725/online-cv) I used. 

[<img src="https://raw.githubusercontent.com/runtheorun-exe/swfiles/main/cv.png" title="click me! i don't bite(much)"  width="400"/>](https://runtheorun-exe.github.io/online-cv)

You can probably see why anything seen here might change in the future. Next steps regarding this assignment would be a PDF conversion and potentially setting up continuous integration? Or just a redesign of the template used. 


## Pull Request #1
You can find all the needed information [here](https://github.com/ioniodi/sitegr/issues/78) but a summary of what happened will follow.
Seeing as I lacked any experience with netlify, .yaml files and almost all other tools used to build our own [Ionian DI](https://epic-hamilton-da9ac8.netlify.app/) website, I chose to perform maybe one of the simplest, self-explanatory tasks available; update the website so it linked to the new [Department President](https://epic-hamilton-da9ac8.netlify.app/people/emagos/).
That's all really. The thought is that for the next PR I will be more comfortable to dive into tougher projects.

## CLI Exercise #1
This one was a hassle and a half.
I chose to work on the [ntfy](https://github.com/dschep/ntfy) assignment. It seemed like the perfect combination of simple and useful. It's worth mentioning that at this point I started this assignment after I had started wokring on the Collaborative Content Assignment, thinking the cli was overdue. Basically I ended up working on two painfully problematic assignments. Back to ntfy.
ntfy offers shell integration and a variety of 3rd party apps one can use to receive notifications on their smartphones et cetera. And generally I believe they could be sorted into two categories: the more straight-forward ones and the less-documented ones (Telegram, and PushBullet respectively). 
I was stubborn enough to push ahead with PushBullet (even though I had been made aware of the fact that Telegram is far more simple). The problem was there seemed to be no clear guidance as to how to tell ntfy the API key I issued from PushBullet. I messed with so many different things settings and files, and 2 virtual boxes and a subsystem ended up being nerfed because I was never able to perform a fresh install of ntfy (and reset the files I had screwed up trying to connect to PushBullet). 
Days later, this cutie appeared:

<img src="https://github.com/runtheorun-exe/swfiles/blob/main/greetings.gif" width="400"/>

Later, after some bashrc magic (aka shell integration for ntfy by appending "$(ntfy shell-integration)" to the .bashrc file) we can be notified when a long-running task has been completed, as seen here:

<img src="https://github.com/runtheorun-exe/swfiles/blob/main/sudoaptget.gif" width="400"/>

An asciicast documenting the installation process is also available:

<a href="https://asciinema.org/a/403568" target="_blank"><img src="https://asciinema.org/a/403568.svg" width="400"/></a>

## Collaborative Work (pibook) #1
For the first part of the CW assignment, we were asked to cover 2 technologies (upload 2 images for each topic, and write an .md caption for each).
hose to cover 2 related programming languages: [Objective-C](https://runtheorun-pi.netlify.app/gallery/objective-c/) and [Swift](https://runtheorun-pi.netlify.app/gallery/swift-md/). Then after some research I wrote up their captions , found [here](https://github.com/runtheorun-exe/_gallery/blob/master/objective-c.md) and [here](https://github.com/runtheorun-exe/_gallery/blob/master/swift.md). Afterwards, I [updated](https://github.com/runtheorun-exe/site/blob/master/_slides/programming.md) the [Programming Slide Set](https://runtheorun-pi.netlify.app/slides/programming/) and added my contributions to the Timeline. Then I simply deployed my repository with the help of netlify at https://runtheorun-pi.netlify.app/.
The pibook repo utilizes submodules, which while being easy to setup, recording with asciinema made things a whole lot harder. But nevertheless, here is the asciicast which not only shows the submodule installation but also almost the entire workflow for this assignment. Did I mention that almost the entire assignment was completed via terminal? (save for some tweaks and image reuploads).

<a href="https://asciinema.org/a/nFsVPoymzZ7iRvLTVW04Pzdjf" target="_blank"><img src="https://asciinema.org/a/nFsVPoymzZ7iRvLTVW04Pzdjf.svg" width="400"/></a>

Not a tough one, but definitely a time-intensive one.

## CV part 2
For the second part of the CV assignment we were tasked to convert our cv into a pdf, which was a pretty straight forward task done with pandoc and the following command:

```
pandoc https://runtheorun-exe.github.io/online-cv/ -f html-native_divs -o cv.pdf --pdf-engine=xelatex
```
This resulted in an (objectively, aesthetically displeasing) [file](https://github.com/runtheorun-exe/online-cv/blob/gh-pages/cv.pdf) which can be seen below

<img src="https://github.com/runtheorun-exe/swfiles/blob/main/Screenshot 2021-04-26 153001.png" width="400"/>

The automation part of this assignment was done with a GitHub Action documented [here](https://github.com/runtheorun-exe/online-cv/blob/gh-pages/.github/workflows/cv2pdf.yml). 

Below lies the code used to make the GH Action:
```yml
name: CV2PDF

on: 
  page_build:
    branches: [gh-pages]
  
jobs:
  convert:
    runs-on: ubuntu-18.04
    steps:  
      - uses: actions/checkout@v2
        with:
         persist-credentials: false
         fetch-depth: 0
      - name: Convert 
        uses: docker://pandoc/latex:2.13
        with:
          args: "https://runtheorun-exe.github.io/online-cv/ -f html-native_divs -o cv.pdf --pdf-engine=xelatex"
      - name: Commit pdf
        run: |
          git config --global user.name 'Theocharis Panagiotis Charalampidis'
          git config --global user.email 'runtheorun-exe@users.noreply.github.com'
          git add -A
          git add .
          git commit -m "Added PDF -auto action"
      - name: Push changes
        uses: ad-m/github-push-action@master
        with:
          github_token: ${{ secrets.GITHUB_TOKEN }}
          branch: ${{ github.ref }}
```          

Since the CV has a GitHub Pages-powered website, the GH Action gets triggered everytime GH Pages has fnished rebuilding the website. This can lead to unnecessary triggers (for instance CSS modifications don't affect the pdf) but seeing as gh Pages needs some time to build the updated website, this solution seemed the best one.


## CLI Exercise #2
For the 2nd CLI Assignment, I chose to work on Huginn. Following the simple installation on Docker, and following [this tutorial](https://github.com/courses-ionio/sw-lab#huginn-agents) I created one website agent and one post agent, the former scraping news from the Ionian University website and the latter pushing them to a channel on slack. Later I added 2 RSS Agents for ThePressProject and CNN Europe. All run every 5 minutes and the Post Agent gets triggered automatically when fresh news are uploaded.

[<img src="https://raw.githubusercontent.com/runtheorun-exe/swfiles/main/Screenshot%202021-04-26%20182535.png" width="400"/>](https://raw.githubusercontent.com/runtheorun-exe/swfiles/main/Screenshot%202021-04-26%20182535.png)

Following mr. Patiniotis' prompt, I went ahead and asciicasted the manual installation process for Huginn which was a disaster at best. Various bugs were found, and while a lot were taken note of and corrected in-flight, there were always new ones poppinh up, and at the end of the day the installation never worked.
Both Docker and CLI versions are the same, since both lead you to the same GUI, but the process was still documented and uploaded here so as to check the CLI part of the exercise.

<a href="https://asciinema.org/a/6AeGkKLoIQsq7TqQfcue6FJ7Y" target="_blank"><img src="https://asciinema.org/a/6AeGkKLoIQsq7TqQfcue6FJ7Y.svg" width="400"/></a>
## CLI Exercise #3
This time, I chose the twilio assignment. As vague as can be, the goal to "deploy an application that forwards a call depending on a white- and black- list of phone numbers" proved to be a tough one. That's on me and my app hosting choices though, but admittedly the twillio documentation is lacking to say the very very best of it.
Jumping through hoops I made a simple SMS webhook which replies with a link to my resume on any message. 

[<img src="https://raw.githubusercontent.com/runtheorun-exe/swfiles/main/twilio.png" width="400"/>](https://raw.githubusercontent.com/runtheorun-exe/swfiles/main/twilio.png)

This is what someone sees when they text my twilio number.
The code is hosted as a Lambda function on AWS (sue me) which itself is nothing more than a function which has 1 line of code: 
```python
return ' <?xml version=\"1.0\" encoding=\"UTF-8\"?>'\
           '<Response><Message><Body>Hello from Theocharis Panagiotis Charalampidis. \nCheck out my resume at https:// (#runtheorun-exe.github.io/online-cv ! </Body></Message></Response>'
```
So basically it just returns a TwiML (Twilio Markup Language) string to the Twilio API that handles the incoming message. The Lambda communicates with Twilio through an API constructed specifically for that.
While on principle, handling a phone tree system is simple, Lambdas are dumb when it comes to Python packages and it's all just a hassle. The upshot of using Lambdas though is that it's theoretically easier to host such Twilio apps.
A Call routing was constructed using Twilio Studio, a Scratch-like environment and it works just fine, but is not pure code and can be seen below.


[<img src="https://raw.githubusercontent.com/runtheorun-exe/swfiles/main/twistudio.png" width="400"/>](https://raw.githubusercontent.com/runtheorun-exe/swfiles/main/twistudio.png)


Once again following mr. Patiniotis' prompt, I went ahead and installed twilio locally and pretty much redid my Lambda SMS function locally, with an asciicast to prove it:

<a href="https://asciinema.org/a/Qgk6MEDdzDFKAkp5iduiE67tt" target="_blank"><img src="https://asciinema.org/a/Qgk6MEDdzDFKAkp5iduiE67tt.svg" width="400"/></a>

And the proof that I really did receive a message:

<img src="https://raw.githubusercontent.com/runtheorun-exe/swfiles/main/twilocal.jpg" width="400"/>

Sources:
* https://www.twilio.com/docs/sms/tutorials/how-to-receive-and-reply-python-amazon-lambda#configuring-our-api-gateway-response
* https://github.com/twilio/twilio-python

# CLI Exercise 4
Hyperfine & PySpy profiling tools.
Using 2 pretty simple python scripts, hello-world.py and randpass.py.
#### hello-world.py
````python
import time

for i in range(100):
    print("Hello World")
    if (i % 10) == 0:
        time.sleep(1)
````

#### randpass.py
````python
import string
import random
import csv
import time

symbols = ['*', '%', '£']  # Can add more
passlist = [ ]
for i in range(100):
    password = ""
    for lngth in range(15):
        password += random.choice(string.ascii_lowercase)
        password += random.choice(string.ascii_uppercase)
        password += random.choice(string.digits)
        password += random.choice(symbols)
        print(password)
        if lngth >= 10:
            passlist.append(password)
            with open('randpass.csv', mode='a') as file_:
                file_.write(password)
                file_.write("\n")
````
One ofthe scripts has artificially been slowed down with `time.sleep()` since the hello-world.py script is ridiculously simple.

Installation of hyperfine and pySpy were done with the following commands:

```shell
pip install py-spy
wget https://github.com/sharkdp/hyperfine/releases/download/v1.11.0/hyperfine_1.11.0_amd64.deb
sudo dpkg -i hyperfine_1.11.0_amd64.deb
git clone https://github.com/brendangregg/FlameGraph.git
```
After some shuffling, we start testing `py-spy` by running the following:
```shell
py-spy record -o profile-hello.svg -- python3 hello-world.py
py-spy record -o profile-rand.svg -- python3 randpass.py
```
These commands produce a .svg file each, seen below.

<img src="https://raw.githubusercontent.com/runtheorun-exe/swfiles/668d343cfad2324c7f061031d8abec375c3ed0d6/profile-hello.svg" title="Click me!" width="400"/>
<img src="https://raw.githubusercontent.com/runtheorun-exe/swfiles/668d343cfad2324c7f061031d8abec375c3ed0d6/profile-rand.svg" title="Click me!" width="400"/>

The actual asciicast outputs of py-spy and the hyperfine results can be found below:

<a href="https://asciinema.org/a/CPjHCJ0ySs5Y8z3JYUnq1M46z" target="_blank"><img src="https://asciinema.org/a/CPjHCJ0ySs5Y8z3JYUnq1M46z.svg" title="PySpy" width="400"/></a>


<a href="https://asciinema.org/a/2W8gRQXYkdEqAOmkSWN80UPUt" target="_blank"><img src="https://asciinema.org/a/2W8gRQXYkdEqAOmkSWN80UPUt.svg" title="hyperfine" width="400" /></a>

Sources:
* https://github.com/sharkdp/hyperfine
* https://github.com/benfred/py-spy

## Collaborative Work (pibook) #2

After uploading the necessary files ([Dijkstra's biography @ site/_biography](https://github.com/runtheorun-exe/site/blob/master/_biography/e-dijkstra.md), 
[the goto case study](https://github.com/runtheorun-exe/_gallery/blob/6f3b413c6fa8c0d277e909444a338b28a822f4f9/goto.md), [a photo of E. W. Dijkstra and a respective thumbnail photo](https://github.com/runtheorun-exe/images/blob/f031c23490c2e387cda506d588d1019e27bbb51b/dijkstra.jpg), [an example of GOTO use case](https://github.com/runtheorun-exe/images/blob/f031c23490c2e387cda506d588d1019e27bbb51b/goto.png), and finally [Dijkstra's biography again, @ extras submodule](https://github.com/runtheorun-exe/extras/blob/56fe63fb8d55b309dd23865c675d2389f616ae63/bio-dijkstra.md)) and a brief submodule installation demo (below) the final part of thw Collaborative Work assignment was done. 
The project has been succesfully built and can be found [here](runtheorun-pi.netlify.app/).
The topics chosen were GOTO's dangerous reputation and the biography of the man who gave GOTO its reputation. 
Sources for the case study and the biography are as follows:
* Dijkstra, E. W. (1968). Letters to the editor: go to statement considered harmful. Communications of the ACM, 11(3), 147–148. doi:10.1145/362929.362947 
* Nagappan, M. (2018). Reconsidering Whether GOTO Is Harmful. IEEE Software, 35(3), 93–95. doi:10.1109/ms.2018.2141020 
* https://www.britannica.com/biography/Edsger-Dijkstra
* https://www.cs.utexas.edu/users/EWD/MemRes(USLtr).pdf

Finally the demo asciicast:

<a href="https://asciinema.org/a/bC8VEtnNgkfRB79JuZqDSPvJq" target="_blank"><img src="https://asciinema.org/a/bC8VEtnNgkfRB79JuZqDSPvJq.svg" width="400"/></a>

## Epilogue

This course started not quite well, and it kept on just like that. A very time-intensive course with all sorts of obstacles and irritating things to deal with. Tiny things, big things, things I chose to do the hard way (looking at you, Lambda Function Twilio), things I did the bare minimum for. Hours and hours of videos and quizzes to be watched and answered.
All in all, this was a pain to complete. But,objectively, the experience gained may come in handy.
Hundreds of commits later, months later, probably weeks spent researching and writing code and reports, more and more courses ignored and assignments dropped to do more here for this course, did eventualy cover the things I hoped to when this started: Learn to move around github, and maybe some extra tools along the way.
Like AWS for instance. (I'll never shut up about that Lambda function, it was the most exhausting assignment I did, but damn did I like the things I learned.)
Maybe, this is a small taste of what's to come.
If it is, I need to know now and drop out.
That's it. Hopefully, tata forever.

P.S. 
3 course assistance meetings were held with mr. Patiniotis, on April 5th,May 10th and 24th. 
## Week 3:
| Marker | Question | Answer |
| --- | --- | --- |
| 1767  | Ποιες ήταν οι βασικές ιδέες που επηρέασαν τον Αλαν Κεη στην κατασκευή νέου λογισμικού; |  Κυριολεκτικά δεν κατάλαβα οτι μιλούσε καν μέχρι εκείνο το σημείο |
| 2237 | Να δώσετε παράδειγμα από την προσωπική σας εμπειρία για λογισμικό με καλή και με κακή αρχιτεκτονική με αναφορά στα κριτήρια της επιλογής σας. | Αρχιτεκτονική λογισμικού ονομάζουμε τον τρόπο με τον οποίο τα διάφορα κομμάτια ενός λογισμικού θα πρέπει να οργανωθούν, να επικοινωνούν μεταξύ τους και υπό ποιους κανόνες και περιορισμούς πρέπει να κυβερνώνται όλα αυτά από το λογισμικό.|
| 2903 | Ποια είναι τα βασικά δομικά στοιχεία στην αρχιτεκτονική του λογισμικού etoys και από που άντλησε ο Αλαν Κέη την έμπνευση για αυτά; | Το σύστημα Etoys βασίζεται στην ιδέα προγραμματιζόμενων εικονικών οντοτήτων που συμπεριφέρονται στην οθόνη του υπολογιστή και παρέχει ένα περιβάλλον δημιουργίας πολυμέσων με ένα απλό, ισχυρό μοντέλο αντικειμένων με σενάριο για πολλά είδη αντικειμένων που δημιουργούνται από τελικούς χρήστες. Δίνει τη δυνατότητα κοινής χρήσης επιτραπέζιων υπολογιστών με άλλους χρήστες Etoys σε πραγματικό χρόνο, ώστε να μπορούν να γίνουν πολλές μορφές καθηλωτικής καθοδήγησης και παιχνιδιού μέσω του Διαδικτύου. Έμπνευση του Etoys αποτελεί η βασική ιδέα των μουσείων, και με βάση τα λόγια του έχει ρόλο και στοχαστικό και ενδοσκοπικό.| 
| 3528 | Ποια είναι κάποια από τα λάθη των σύγχρονων λειτουργικών συστημάτων σύμφωνα με τον Αλαν Κέη; | Η γενικότερη τάση στα λειτουργικά συστήματα φαίνεται να είναι η δημιουργία διεπαφών γραφικών που δεν είναι τόσο εύχρηστες όσο θα μπορούσαν να είναι για τον χρήστη, περιορίζοντας έτσι την παραγωγικότητά του και δυσχεραίνοντας την προσαρμογή του χρήστη στο νέο γραφικό περιβάλλον.|

## Week 6:
| Marker | Question | Answer |
| --- | --- | --- |
| 320 | Είναι χρήσιμα στην πληροφορική τα μαθήματα των μαθηματικών που κάνατε στο 1ο έτος και γιατί; |  Math, as taught in universities is incompatible with Computer Science due to their theorems that are long, complicated and are dealing with infinity, something that computers can't work with.  |
| 815 | Είναι η πληροφορική επιστήμη ή κλάδος των μηχανικών; ποια είναι τα κριτήρια για να ανήκει σε κάποιον από αυτούς τους κλάδους; | None of the above. CS is still developing thus categorizing it now could lead to issues in the future. Engineering is defined by Alan Kay as the ability for a massive project to be completed in a short amount of time and with as few people possible who can work together efficiently.|
| 1346 | Γιατί οι περισσότεροι δεν μπορούν να καταλάβουν τις ιδέες του Νταγκλας Ενγκελμπαρτ για την διάδραση με ψηφιακά συστήματα; | Essentially people are instrumental reasoners. If a tool can't help them in their life, they diregard it and don't try to understand it.| 
| 1700 | Ποιες ήταν οι θεμελιώδεις εμπνεύσεις και αναλογίες για την δουλειά του; |Sketchpad, along with Sutherland's thesis on Sketchpad .|
| 2002 | Ποια είναι τα βασικά προβλήματα της 3βάθμιας εκπαίδευσης στην πληροφορική; | The lack of projects at universities, as understood by the museum example. Students need to be exposed to a lot of different ideas and projects before they find what suits them and follow that path.| 
| 2749  | Πως διαφέρει ο αντικειμενοστραφής προγραμματισμός που περιγράφει από αυτόν που διδαχτήκατε στο αντίστοιχο μάθημα; | Object-oriented systems changed in regards to the way inheritance works, but my understanding of OOP is lacking.| 

## Week 7
| Question | Answer |
| --- | --- |
| Ποια πρέπει να είναι τα κριτήρια της αξιολόγησης στην εκπαίδευση και στο λογισμικό αν ο στόχος είναι η καινοτομία;| Όσο και αν η ανάγκη για καινοτομία μας προκαλεί να δράσουμε άμεσα, θα πρέπει οι κινήσεις μας να είναι αποτέλεσμα σκέψης και προσεκτικού σχεδιασμού.|
| Πως μπορούμε να φτιάξουμε σήμερα το λογισμικό για τους υπολογιστές που θα έχουμε σε δέκα ή περισσότερα χρόνια;| Θα μπορούσαμε να αντλήσουμε έμπνευση από το πως δημιουργήθηκαν οι πρώτοι υπολογιστές, τι μας οδήγησε στη δημιουργία τους.|
| Ποια είναι η αναλογία του ποδήλατου με βοηθητικές ρόδες για την περίπτωση του λογισμικού;| Όπως όταν κάνει κανείς ποδήλατο με βοηθητικές και δεν μαθαίνει πραγματικά ποδήλατο, έτσι και εδώ, δημιουργείται ένα πολύ αποστειρωμένο περιβάλλον στο οποίο είναι αδύνατο να δημιουργηθεί μια πραγματικά λειτουργική λύση.
| Για ποιο λόγο είναι δύσκολη η κατασκευή λογισμικού διεπαφής με τον χρήστη; | Κάθε χρήστης έχει διαφορετικούς τρόπους να δουλεύει, άρα προφανώς είναι δύσκολο να δημιουργηθεί μια διεπαφή που θα εξυπηρετεί όλους τους χρήστες ή έστω μια μεγάλη μερίδα αυτών.|
| Πως πρέπει να είναι οργανωμένη μια ομάδα για να αντιμετωπίσει με την βοήθεια της πληροφορικής δύσκολες αποφάσεις και τι σημαίνει αυτό για την οργάνωση μιας ομάδας που βρίσκεται στην διαδικασία της εκπαίδευσης; | Ο Kay συστήνει ομαδική συνεργασία και προσέγγιση λύσεων όπως το κάνουν οι υπολογιστές (με τη μέθοδο διαίρει και βασίλευε όπου ένα προβλημα σπαει σε υποπροβλήματα) |
## Week 8:
| Question | Answer |
| --- | --- |
| Ποια είναι η τεχνολογική λύση για το πρόβλημα της οικονομικής ανισότητας που δημιουργεί η συγκέντρωση οικονομικού κεφαλαίου σε λίγους;| Σύμφωνα με τον Jaron Lanier η τεχνολογική λύση είναι να έχουμε ένα "Universal Micro-payment System", όπου θα καταγράφει τι συνεισφέρουν οι άνθρωποι στο ψηφιακό οικοσύστημα. Έτσι ακόμα και αν τα μηχανήματα είναι πάρα πολύ εξελιγμένα και τα θεωρούμε ως αυτόνομα, πάντα θα εξαρτώνται από τα πληροφοριακά συστήματα που θα έχουν δημιουργήσει οι άνθρωποι. Δεν αρκεί μόνο η σωστή κατασκευή και ρύθμιση αυτών αλλά και η συνεχή τους συντήρηση. Συνεπώς όλο αυτό θα μας οδηγήσει σε ένα νέο οικονομικό σύστημα.|
| Για ποιο λόγο η τεχνολογία της αντιγραφής και επικόλλησης είναι ασύμβατη με τους δικτυωμένους υπολογιστές;| Σύμφωνα με τον Jaron Lanier στην περίπτωση ενός τέτοιου συνδεδεμένου δικτύου υπολογιστών, δεν υπάρχει λόγος για copy-paste πληροφοριών, καθώς το πρωτότυπο θα βρίσκεται πάντα εκεί. Προτείνει την αναφορά και όχι κάποιο ανούσιο copy-paste.|
| Ποιες είναι οι οικονομικές, πολιτισμικές, και πολιτικές επιπτώσεις της τεχνολογικής επιλογής των μονόδρομων υπερσυνδέσμων στα ψηφιακά έγγραφα;| Το κοινωνικό αντίκτυπο της παρούσας δομής του διαδικτύου είναι η αναγκαστική ιδιωτικοποίησή του ώστε να συντηρηθεί λόγω του σχεδιασμού του. Αυτό οδηγεί στο πολιτικό ζήτημα, όπου η δομή του διαδικτύου έχει σαν αποτέλεσμα την "αποδημοκρατικοποίηση" του διαδικτύου και της πληροφορίας. Θα πρέπει να υπάρχει κατανομή στη δυνατότητα χρήσης πληροφοριών, προς αποφυγή εισοδηματικής ανισότητας.
| Ποιες είναι οι βασικές συνεισφορές του Ted Nelson στην τεχνολογία σύμφωνα με τον Jaron Lanier και πως διαφέρουν από την τεχνολογία που έχουμε τώρα; | Ο Ted Nelson συνείσφερε στη διαφορά μεταξύ της υποθετικής και της εξουσιοδοτημένης πρόσβασης πληροφοριών. Παραθέτει το παράδειγμα εξάλειψης ρόλων εξαιτίας των μηχανών, όπως στην περίπτωση των μεταφραστών. Τέλος αναφέρει πως κάθε μορφή τεχνητής νοημοσύνης αποτελεί τελικά μια μορφή αποδυνάμωσης του ανθρώπινου εγκεφάλου.|
## Week 9
| Question | Answer |
| --- | --- |
| Με ποιο τρόπο συνεργαστήκατε σε ιδέες δικές σας και άλλων σε αυτό το μάθημα;|Παρά την πληθώρα εργαλείων που μας προτάθηκαν στη διάρκεια του μαθήματος (Tmate ,IRC, Mumble), καλώς ή κακώς υπήρχαν ήδη εργαλεία και κανάλια επικοινωνίας τα οποία προτιμήθηκαν κυρίως για λόγους ταχύτητας και αποδοτικότητας.|
| Το καλύτερο μάθημα που παρακολούθησε ο Αλαν Κεη ως φοιτητής του έδωσε γνώσεις πάνω σε συστήματα που υπήρχαν;|Κατά τη διάρκεια των σπουδών του ο Kay παραοκολούθησε το μάθημα Advanced System Design κατά το οποίο ο καθηγητής του μαθήματος προσπάθησε να καθαρίσει τα μυαλά των φοιτητών του απο τον τρόπο σκέψης που είχαν, με σκοπό να μπορέσουν να αποκομίσουν νέες γνώσεις και ιδέες.|
| Σε ποια εταιρεία αναφέρεται και γιατί είναι πρόβλημα να έχουμε πολλές γραμμές κώδικα;| Αναφέρεται στην Microsoft, και τη φέρνει ως παράδειγμα για να τονίσει πως όσο μεγαλώνει ο κώδικας τόσο αυξάνεται η πολυπλοκότητα και μειώνεται η ευκολία εύρεσης bug.|
| Με τι μοιάζει το λογισμικό σήμερα και ποιο είναι ένα καλύτερο παράδειγμα για το μέλλον αναφορικά με την αρχιτεκτονική και τον τρόπο ανάπτυξης του; | Το λογισμικό μοιάζει όλο και πιο πολύ με πολύπλοκο μηχανισμό. Ένα καλό παράδειγμα για το πως θα μπορούσε να εξελιχθεί η αρχιτεκτονική και ο τρόπος ανάπτυξης του λογισμικού είναι μια προσπάθεια να δημιουργηθεί διαδραστικό λογισμικό το οποίο θα μπορεί να αναπροσαρμόζεται ανάλογα με τις ανάγκες του χρήστη. |
| Γιατί δεν αρκεί η εξυπνάδα και οι γνώσεις και απαιτείται όραμα, ποιο είναι το πρόβλημα με την δημοφιλή Javascript; | Η Javascript ούσα αντικειμενοστραφής γλώσσα δεν μπορεί να λύσει πολλά προβλήματα ,με αποτέλεσμα ο κώδικας που δημιουργείται από αυτή να είναι αρκετά περιορισμένος.|
| Με ποιο τρόπο το μάθημα μας εφαρμόζει στην πράξη τις συμβουλές του Αλαν Κέη αναφορικά με την αξία παλιών ιδεών και εργαλείων; | Το μάθημα ‘Τεχνολογίες Λογισμικού’ διδάσκει διαχρονικά εργαλεία και πεποιθήσεις παλαιότερων ετών, που στιγμάτισαν τον κόσμο της Πληροφορικής. Συγκεκριμένα, υπάρχουν πολλές αναφορές στα άτομα-εφευρέτες, στον τρόπο κατασκευής και λειτουργίας των λογισμικών, ενώ ταυτόχρονα προσπαθεί να μας ωθήσει να αντιληφθούμε τις διαφορές μεταξύ των τότε ιδεών και εργαλείων με τα σημερινά αντίστοιχα. 
## Week 10
| Question | Answer |
| --- | --- |
|Με ποιο τρόπο το μάθημα μας σας εκπαιδεύει να εντοπίζετε νέα προβλήματα αντί να λύνετε προβλήματα που σας δίνονται έτοιμα;| Το μάθημα ‘Τεχνολογίες Λογισμικού διδάσκεται με συγκεκριμένο τρόπο, με τον οποίο ωθεί τους μαθητές να αναζητούν νέες προσωπικές λύσεις και εργαλεία για την επίλυση των ήδη υπάρχοντων προβλημάτων. Ωστόσο, κατά τη διάρκεια της προαναφερόμενης διαδικασίας, είναι πιθανή η δημιουργία νέων ζητημάτων. |
|Γιατί ο Αλαν Κέη χρησιμοποιεί ένα σύστημα χωρίς εφαρμογές και αρχεία και κάνει την παρουσιάση του χωρίς Powerpoint, τι θέλει να μας πει για την τεχνολογία λογισμικού με αυτήν την επιλογή του;| Ο Αλαν Κευ, χρησιμοποιεί το σύστημα ‘Frank’ για την παρουσίαση του, το οποίο μπορούμε να το σκεφτούμε ως ένα λειτουργικό σύστημα. Παρατηρώντας τις ομιλίες και τις πεποιθήσεις του μπορούμε να αντιληφθούμε ότι προτιμούσε διαφορετικά εργαλεία από τα ευρέως γνωστά και η δυνατότητα διάδρασης και επεξεργασίας πολλών τύπων αρχείων σε ένα παράθυρο συντελεί στην χρησιμοποίηση του . Επιπλέον, το σύστημα αυτό αποτελείται από 20 χιλιάδες γραμμές κώδικα εν αντιθέσει με τα γνωστά ΛΣ, που κατέχουν τουλάχιστον 200 εκατομμύρια γραμμές, γεγονός που αποτελεί έναν ιδιαίτερο λόγο χρήσης, όπως αναφέρει και στην συγκεκριμένη ομιλία του.|

