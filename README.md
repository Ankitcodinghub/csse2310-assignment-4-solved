# csse2310-assignment-4-solved
**TO GET THIS SOLUTION VISIT:** [CSSE2310 Assignment 4 Solved](https://www.ankitcodinghub.com/product/csse2310-weighting-15-solved-3/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;120336&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;3&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (3 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSSE2310 Assignment 4 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (3 votes)    </div>
    </div>
1

The goal of this assignment is to further develop your C programming skills, and to demonstrate your un- 2

derstanding of networking and multithreaded programming. You are to create two programs which together 3

implement a brute-force password cracking system. One program – crackserver – is a network server which 4

accepts connections from clients (including crackclient which you will implement). Clients connect, and pro- 5

vide encrypted passphrases that the server will attempt to crack (recover the original unencrypted passphrase). 6

crackclient and crackserver is over TCP using a newline-terminated text command protocol. Advanced 8

functionality such as connection limiting, signal handling and statistics reporting are also required for full 9

The assignment will also test your ability to code to a particular programming style guide and to use a 11

revision control system appropriately. 12

Student Conduct 13

the assignment specification with fellow students, including on the discussion forum. In general, questions like 15

“How should the program behave if hthis happensi?” would be safe, if they are seeking clarification on the 16

specification. 17

You must not actively help (or seek help from) other students or other people with the actual design, structure 18

and/or coding of your assignment solution. It is cheating to look at another student’s assignment code 19

and it is cheating to allow your code to be seen or shared in printed or electronic form by others. 20

collusion, formal misconduct actions will be initiated against you, and those you cheated with. That’s right, if 22

you share your code with a friend, even inadvertently, then both of you are in trouble. Do not post your 23

code to a public place such as the course discussion forum or a public code repository. (Code in private posts 24

extensions so do not post your code to any public repository until at least three months after the result release 26

access your computer – you must keep your code secure. Never leave your work unattended. 28

You must follow the following code referencing rules for all code committed to your SVN repository 29

(not just the version that you submit): 30

Introduction

Code Origin Usage/Referencing

Code provided to you in writing this semester by

Code you have personally written this semester for

Code you have personally written in a previous enrolment

in this course or in another ITEE course and where that code has not been shared or published.

Code (in any programming language) that you have taken inspiration from but have not copied .

Code Origin Usage/Referencing

ASCII text file (named toolHistory.txt) is included in your repository and with your submission that describes in detail how the tool was used. If such code is used without appropriate referencing and without inclusion of the toolHistory.txt file then this will be considered misconduct.

31

many cooperate with us in misconduct investigations. 33

The teaching staff will conduct interviews with a subset of students about their submissions, for the purposes 34

of establishing genuine authorship. If you write your own code, you have nothing to fear from this process. If 35

you legitimately use code from other sources (following the usage/referencing requirements in the table above) 36

then you are expected to understand that code. If you are not able to adequately explain the design of your 37

solution and/or adequately explain your submitted code (and/or earlier versions in your repository) and/or 38

be able to make simple modifications to it as requested at the interview, then your assignment mark will be 39

subject to a misconduct investigation where your interview responses form part of the evidence. Failure to 41

submission (particularly from artificial intelligence tools) is likely to increase the probability of your selection 43

for an interview. 44

In short – Don’t risk it! If you’re having trouble, seek help early from a member of the teaching staff. 45

Don’t be tempted to copy another student’s code or to use an online cheating service. Don’t help another 46

relationship. You should read and understand the statements on student misconduct in the course profile and 48

49

Simple encryption and salting 50

Hashing is a common method of protecting sensitive data such as passwords. Instead of storing or transmitting 51

the password itself (plaintext) where it is at risk of interception, the password is first transformed by passing 52

it through a one-way function called a hash, yielding the ciphertext. A one-way function is one that is easy to 53

apply in one direction (plaintext to ciphertext), but impossible to apply in the reverse. 54

Because hash functions are deterministic, identical passwords encrypted with a hash function yield identical 55

ciphertext, which can assist an adversary in compromising a system. For this reason, the hashing scheme is 56

usually extended with a method called salting. The plaintext is extended with a random value, or salt, prior 57

to applying the hash function. The salt is stored along with the encrypted password, as both are required to 58

verify a given password and its hash. 59

With a sufficiently large possible range of salt values, this helps prevent attackers from building tables that 60

store the hash results of every possible (salted) password, increasing security by making the cracking more 61

challenging. 62

libcrypt is a POSIX library that supports a wide range of hashing functions and salting schemes – in this 63

assignment you will use it in its simplest mode. Note that this mode is now considered obsolete, and should 64

not be used for protecting data in modern systems. 65

The crypt() function is all that is required. In the simplest mode it is used as follows: 66

Uploading or otherwise providing the assignment specification or part of it to a third party including online

char *cipher = crypt(plaintext, salt)

plaintext salt 67

containing the salt. Only the first 8 characters of plaintext are used, and only the first two characters of salt 68

are used. Any additional characters are ignored. 69

Additionally, the salt must only contain characters from the following character set: 70

a b c d e f g h i j k l m n o p q r s t u v w x y z 71

A B C D E F G H I J K L M N O P Q R S T U V W X Y Z 72

0 1 2 3 4 5 6 7 8 9 . / 73

The return value from crypt() is a pointer to a static buffer, so the caller must copy this before making 74

any further calls to crypt(). A reentrant version of crypt() called crypt_r() is also available – refer to the 75

man page for details and usage. 76

Here are some examples: 77

• plaintext “foobar”, salt “AA” → ciphertext “AAZk9Aj5/Ue0E” 78

• plaintext “dinosaur”, salt “0z” → ciphertext “0zD1fV.Yez8RI” 79

Notice how the supplied salt characters always form the first two characters of the encrypted string. 80

81

The crypt() family of functions is declared in &lt;crypt.h&gt;, and you will need to link your crackserver with 82

the -lcrypt argument to use them in your programs. 83

Specification – crackclient 84

The crackclient program provides a command line interface that allows you to interact with crackserver as 85

a client – connecting to the server, sending crack and encryption requests, and displaying the results. 86

To implement this functionality, crackclient will only require a single thread. 87

Command Line Arguments 88

Your crackclient program is to accept command line arguments as follows: 89

./crackclient portnum [jobfile] 90

• The mandatory portnum argument indicates which localhost port crackserver is listening on – either 91

numerical or the name of a service. 92

• The optional jobfile argument specifies the name of a file to be used as input commands. If not specified, 93

then crackclient is to read input from stdin. 94

crackclient behaviour 95

If an incorrect number of command line arguments are provided then crackclient should emit the following 96

message (terminated by a newline) to stderr and exit with status 1: 97

where is a pointer to a string containing the plaintext password, and is a pointer to a string

Usage: crackclient portnum [jobfile]

If the correct number of arguments is provided, then further errors are checked for in the order below. 98

Job file error 99

If a job file is specified, and crackclient is unable to open it for reading, crackclient shall emit the following 100

message (terminated by newline) to stderr and exit with status 2: 101

crackclient: unable to open job file “jobfile”

where jobfile is replaced by the name of the specified file. Note that the file name is enclosed in double quote 102

characters. 103

Connection error 104

If crackclient is unable to connect to the server on the specified port (or service name) of localhost, it shall 105

emit the following message (terminated by a newline) to stderr and exit with status 3: 106

crackclient: unable to connect to port N

crackclient runtime behaviour 108

Assuming that the commandline arguments are without errors, crackclient is to perform the following actions, 109

in this order, immediately upon starting: 110

• connect to the server on the specified port number (or service name) – see above for how to handle a 111

connection error; 112

• read commands either from the jobfile, or stdin, and process them as described below; and 113

• when EOF is received on the input stream (job file or stdin), crackclient shall close any open network 114

connections, and terminate with exit status 0. 115

If the network connection to the server is closed (e.g. crackclient detects EOF on the socket), then 116

crackclient shall emit the following message to stderr and terminate with exit status 4: 117

crackclient: server connection terminated

Note that crackclient need only detect EOF on the socket when it is reading from the socket. It will 118

only do this after it has read a line from the jobfile (or stdin), sent that to the server, and is then awaiting 119

a response. It is not expected that crackclient will detect EOF on the network socket while it is waiting to 120

read from stdin. 121

crackclient shall interpret its input commands as follows: 122

• Blank lines (i.e. those lines containing no characters), and those beginning with the # character (comment 123

lines), shall be ignored 124

• All other lines shall be sent unaltered to the server (no error checking is required or to be performed) 125

Upon sending a command to the server, crackclient shall wait for a single line reply, and interpret it as follows: 126

• Response “:invalid” → emit the following text to stdout: 127

Error in command

• Response “:failed” → emit the following text to stdout: 128

Unable to decrypt

• Otherwise, the raw output received from the server shall be output to stdout. 129

Your crackclient program is not to register any signal handers nor attempt to mask or block any signals. 130

crackclient example usage 131

The following is an example of an interactive session with crackclient (assuming the crackserver is listening 132

on port 49152). Lines in bold face are typed interactively on the console, they are not part of the output of 133

the program: 134

$ ./crackclient 49152

# A comment line – ignored

# A blank line – ignored

# A malformed crypt request (no salt) crypt chicken

Error in command

# A malformed crypt request (bad salt) crypt chicken %%

Error in command # Valid crypt requests crypt dog K9

K930xTkdzhuMg crypt foobar zZ zZT8RjNYjMLz2

# Invalid crack request – no thread count specified crack zZT8RjNYjMLz2

Error in command

# Failed crack request – the plaintext is not in the dictionary crack zZT8RjNYjMLz2 10

Unable to decrypt

# Successful crack request, 1 thread crack K930xTkdzhuMg 1 dog

# Successful crack request, 10 threads crack K930xTkdzhuMg 10 dog

# Misc invalid crack requests crack K930xTkdzhuMg 0

Error in command crack K930xTkdzhuMg -1

Error in command crack K930xTkdzhuMg 100

Error in command crack K930xTkdzhuMg 1X

Error in command

crackserver 135

this example (and the next) was not using the default dictionary. The plaintext foobar can be found in the 136

default dictionary but was not in the dictionary used in these examples. 137

The following is an example of a file driven session with crackclient (assuming the crackserver is listening 138

on port 49152). Lines in bold face are typed interactively on the console, they are not part of the output of 139

the program, given that cmd.in has the following contents: 140

Note that not all possible error conditions are present in this example. Note also that the for

# this is cmd.in – a list of commands to input to crackclient

# A comment line – ignored

# A blank line – ignored

# A malformed crypt request (no salt) crypt chicken

# A malformed crypt request (bad salt) crypt chicken %% # Valid crypt requests crypt dog K9 crypt foobar zZ

# Invalid crack request – no thread count specified crack zZT8RjNYjMLz2

# Failed crack request – the plaintext is not in the dictionary crack zZT8RjNYjMLz2 10

# Successful crack request, 1 thread crack K930xTkdzhuMg 1

# Successful crack request, 10 threads crack K930xTkdzhuMg 10 # Misc invalid crack requests crack K930xTkdzhuMg 0 crack K930xTkdzhuMg -1

1

2

3

4

5

6

7

8

9 10

11

12

13

14

15

16

17

18

19

20

21

22

crack K930xTkdzhuMg 100 crack K930xTkdzhuMg 1X

23

24

$ ./crackclient 49152 cmd.in

Error in command

Error in command K930xTkdzhuMg zZT8RjNYjMLz2

Error in command Unable to decrypt dog dog

Error in command

Error in command

Error in command

Error in command

141

crackserver is a networked, multithreaded password cracking server, allowing clients to connect and provide 142

encrypted ciphertext for cracking, and also allows clients to provide plaintext passwords for encrypting. All 143

communication between clients and the server is over TCP using a simple command protocol that will be 144

described in a later section. 145

Command Line Arguments 146

Your crackserver program is to accept command line arguments as follows: 147

./crackserver [–maxconn connections] [–port portnum] [–dictionary filename] 148

In other words, your program should accept up to three optional arguments (with associated values) – which 149

can be in any order. 150

The connections argument, if specified, indicates the maximum number of simultaneous client connections 151

operating system limits which we will not test). 153

Important: Even if you do not implement the connection limiting functionality, your program must correctly 154

handle command lines which include that argument (after which it can ignore any provided value – you will 155

The portnum argument, if specified, indicates which localhost port crackserver is to listen on. If the port 157

number is absent or zero, then crackserver is to use an ephemeral port. 158

The dictionary filename argument, if specified, indicates the path to a plain text file containing one word 159

or string per line, which represents the dictionary that crackserver will search when attempting to crack 160

passwords. If not specified, crackserver shall use the system dictionary file /usr/share/dict/words. 161

Program Operation 162

The crackserver program is to operate as follows: 163

• If the program receives an invalid command line then it must print the message: 164

Specification – crackserver

Usage: crackserver [–maxconn connections] [–port portnum] [–dictionary filename]

to stderr, and exit with an exit status of 1. 165

– any of –maxconn, –port or –dict does not have an associated value argument 167

– the maximum connections argument (if present) is not a non-negative integer 168

– the port number argument (if present) is not an integer value, or is an integer value and is not either 169

zero, or in the range of 1024 to 65535 inclusive 170

– 171

– any additional arguments are supplied 172

• If the dictionary filename argument refers to a file that does not exist or cannot be opened for reading, 173

crackserver shall emit the following error message to stderr and terminate with exit status 2: 174

any of the arguments is specified more than once

crackserver: unable to open dictionary file “filename”

where filename is replaced by the name of the dictionary file provided on the command line. Note that 175

the double quote characters must be present. 176

• The dictionary words must be read into memory. Lines in the dictionary are terminated by newline 177

characters (except possibly the last line) and each line (excluding that newline character) is considered 178

to be a word. Any words longer than 8 characters should be discarded, i.e. not saved into memory, as 179

the crypt() family of functions only considers at most 8 characters of any supplied plain text. The order 180

crackserver must read the dictionary only once. 183

• If the dictionary contains no words that are 8 characters long or shorter, then crackserver shall emit the 184

following error message to stderr and terminate with exit status 3: 185

crackserver: no plain text words to test

• If portnum is missing or zero, then crackserver shall attempt to open an ephemeral localhost port for 186

listening. Otherwise, it shall attempt to open the specified port number. If crackserver is unable to listen 187

on either the ephemeral or specified port, it shall emit the following message to stderr and terminate 188

with exit status 4: 189

crackserver: unable to open socket for listening

• Once the port is opened for listening, crackserver shall print to stderr the port number followed by a 190

single newline character and then flush the output. In the case of ephemeral ports, the actual port 191

number obtained shall be printed, not zero. 192

• Upon receiving an incoming client connection on the port, crackserver shall spawn a new thread to 193

handle that client (see below for client thread handling). 194

• If specified (and implemented), crackserver must keep track of how many active client connections exist, 195

and must not let that number exceed the connections parameter. See below on client handling threads 196

for more details on how this limit is to be implemented. 197

• Note that all error messages above must be terminated by a single newline character. 198

• The crackserver program should not terminate under normal circumstances, nor should it block or 199

otherwise attempt to handle SIGINT. 200

• Note that your crackserver must be able to deal with any clients using the correct communication 201

protocol, not just crackclient. Testing with netcat is highly recommended. 202

Client handling threads 203

A client handler thread is spawned for each incoming connection. This client thread must then wait for commands 204

from the client, one per line, over the socket. The exact format of the requests is described in the Communication 205

protocol section below. 206

As each client sends crack requests to crackserver, it the client thread shall spawn threads to perform 207

the brute-force password cracking action against the dictionary. The number of cracking threads spawned per 208

crack request will be specified as part of the request. Even if only one cracking thread is requested, the client 209

thread must spawn an additional thread to do the cracking. 210

is not computationally expensive and there is no need to spawn an additional thread for this operation. 212

crackserver 213

mutual exclusion around any shared data structure(s) to ensure that these do not get corrupted. 214

Once the client disconnects or there is a communication error on the socket then the client handler thread 215

is to close the connection, clean up and terminate. Other client threads and the crackserver program itself 216

must continue uninterrupted. 217

Password cracking 218

crackserver is to use a brute-force method for cracking passwords as follows: 219

220

For each received ciphertext password 221

• Extract the password salt (the first two characters of the ciphertext) 222

• For each word saved from the dictionary 223

– encrypt the word with the salt using crypt() or crypt_r() 224

– compare the sample ciphertext with the encrypted dictionary word 225

– if the two ciphertexts are the same, terminate the search and return the plaintext dictionary word 226

Note – with just over 200,000 words of the right length in the default dictionary on moss and 64 possible 227

salt strings, it is not feasible to pre-calculate and store all possible salt+word combinations. Your program is 228

expected to use the brute-force method described above, trading CPU work for memory storage. 229

The above brute-force algorithm is trivially parallelised across multiple threads. If you implement it, and the 230

client requests more than one thread be used for cracking, you must distribute the dictionary roughly equally 231

across all threads as described below: 232

If the dictionary contains D words and N threads are requested then: 233

• if D &lt; N or N = 1 then only one thread must be used 234

• if D ≥ N and N ≥ 2 then N − 1 threads must each cover bD/Nc words (i.e. D divided by N rounded 235

down if necessary to the nearest integer) and the remaining thread must cover the remaining words 236

Words must be allocated in groups based on the order they are present in the dictionary, i.e., the first bD/Nc 237

words saved from the dictionary must be allocated to one thread, the next bD/Nc words to another thread, etc. 238

For example, if there are 100,000 words saved from the dictionary spread across 7 threads – one thread will 239

get the first b100000/7c = 14285 words, the next thread will be allocated the next 14285 words, etc., and the 240

last (seventh) thread gets the last 14290 words saved from the dictionary. 241

Each thread must check its allocated words in the same order as they are present in the dictionary. 242

If a match is found then the thread that found the match must (a) indicate to the other threads in the job 243

that they should stop work immediately, and (b) not check any further of its own words. You must not use 244

pthread_cancel() to terminate other threads2. It is recommended that you set a (volatile) flag variable that 245

is checked in other threads before each word is processed. 246

multiple times in the dictionary. 249

SIGHUP handling (Advanced) 250

Upon receiving SIGHUP, crackserver is to emit (and flush) to stderr statistics reflecting the program’s oper- 251

• Total number of clients connected (at this instant) 253

• The total number of clients that have connected and disconnected since program start 254

• The total number of crack requests received (since program start), including invalid requests 255

• The total number of valid but unsuccessful crack requests completed (since program start) 256

• The total number of valid but successful crack requests completed (since program start) 257

• The total number of crypt requests received (since program start), including invalid requests 258

crypt() crypt_r() crack 259

performance. It must be updated before any response to a crypt or crack request is sent. 261

Unsuccessful crack requests include those that fail to find a matching dictionary word. Successful crack 262

requests are those that are valid and for which a matching dictionary word is found. Invalid crack requests 263

are those that have the correct command word (crack) but are otherwise invalid (e.g. have invalid arguments). 264

not yet known whether the request is successful or unsuccessful. (See the Communication protocol section for 266

details.) 267

The required format is illustrated below. Each of the six lines is terminated by a single newline. You can 269

assume that all numbers will fit in a 32-bit unsigned integer, i.e. you do not have to consider numbers larger 270

than 4,294,967,295.

Listing 1: crackserver SIGHUP stderr output sample 271

• The total number of calls to and/or (since program start) – including for both

Connected clients: 4

Completed clients: 20

Crack requests: 37

Failed crack requests: 15

Successful crack requests: 19 Crypt requests: 34 crypt()/crypt_r() calls: 34873425

1

2

3

4

5

6

7

Note that to accurately gather these statistics and avoid race conditions, you will need some sort of mutual 272

exclusion protecting the variables holding these statistics. 273

Global variables are not to be used to implement signal handling. See the Hints section below for how you 274

can implement this. 275

Client connection limiting (Advanced) 276

If the connections feature is implemented and a non-zero command line argument is provided, then crackserver 277

must not permit more than that number of simultaneous client connections to the server. crackserver shall 278

maintain a connected client count, and if a client beyond that limit attempts to connect, it shall block, in- 279

definitely if required, until another client leaves and this new client’s connection request can be accept()ed. 280

Clients in this waiting state are not to be counted in statistics reporting – they are only counted once they have 281

properly connected. 282

HTTP connection handling (CSSE7231 students only) 283

CSSE7231 students shall, in addition, implement a simple HTTP server in their crackserver implementa- 284

tion. Upon startup, crackserver shall check the value of the environment variable A4_HTTP_PORT. If set, then 285

crackserver shall also listen for connections on that port number (or service name). 286

If crackserver is unable to listen on that port or service name then it shall emit the following message to 287

stderr and terminate with exit status 5: 288

crackserver: unable to open HTTP socket for listening

The ability to listen on this port is checked after the ability to listen on the “main” port (i.e. the one given 289

on the command line). If the A4_HTTP_PORT environment variable is not set then crackserver shall not listen 290

on any additional ports and shall not handle these HTTP connections. 291

The communication protocol uses HTTP. The connecting program (e.g. netcat, or a web browser) shall 292

send HTTP requests and crackserver shall send HTTP responses as described below. The connection between 293

be ignored by the respective server/client. Note that interaction between a client on the HTTP port and 296

crackserver is synchronous – any one client can only have a single request underway at any one time. This 297

greatly simplifies the implementation of the crackserver HTTP connection handling threads. 298

The only supported request method is a GET request in the following format: 299

GET /stats HTTP/1.1 300

– Description: the client is requesting statistics from crackserver 301

– Request 302

∗ Request Headers: none expected, any headers present will be ignored by crackserver. 303

∗ Request Body: none, any request body will be ignored 304

– Response 305

∗ Response Status: 200 (OK). 306

∗ Response Headers: the Content-Length header with correct value is required (number of bytes 307

in the response body), other headers are optional. 308

∗ Response Body: the ASCII text containing the same crackserver statistics information de- 309

scribed in the SIGHUP handling section above. 310

If crackserver receives an invalid HTTP request then it should close the connection to that requestor (and 311

• Request:

313

NOT included in the client count statistics. 314

Program output 315

Other than error messages, the listening port number, and SIGHUP-initiated statistics output, crackserver is 316

not to emit any output to stdout or stderr. 317

Communication protocol 318

The communication protocol between clients and crackserver uses simple newline-terminated text message 319

strings as described below. Messages from client to server are space delimited. Messages from server to client 320

are colon delimited. Note that the angle brackets &lt;foo&gt; are used to represent placeholders, and are not part of 321

the command syntax. 322

Supported messages from crackclient to crackserver are: 323

• crack &lt;ciphertext&gt; &lt;crackthreads&gt; – the client is requesting the string &lt;ciphertext&gt; be cracked, 324

using the specified number of threads. 325

326

IMPORTANT: even if you do not implement multi-threaded parallel password cracking functional- 327

ity, your crackserver must still accept and parse/validate the &lt;crackthreads&gt; field – it will simply be 328

ignored during the cracking process. 329

• crypt &lt;string&gt; &lt;salt&gt; – the client is requesting the server to encrypt the supplied &lt;string&gt; using the 330

specified &lt;salt&gt;. 331

Single spaces are used as separators between fields, which implies that &lt;ciphertext&gt; and &lt;string&gt; fields 332

must not contain spaces. 333

Supported messages from crackserver to crackclient are 334

• :invalid – sent by the server to a client if the server receives an invalid command from that client (see 335

below) 336

• :failed – sent by the server to a client if the server is unable to crack the supplied ciphertext 337

• &lt;plaintext&gt; – if the server is able to decrypt the ciphertext, then the decrypted plaintext is sent back 338

on a single line. 339

• &lt;ciphertext&gt; – the ciphertext result of a crypt operation is sent back on a single line 340

Invalid commands that might be received by crackserver from a client include: 341

• Invalid command word – an empty string or a command word which is not crack or crypt 342

• Invalid arguments such as 343

terminate the thread associated with that connection). Similarly, if a HTTP client disconnects, crackserver should 312 handle this gracefully and terminate the thread associated with the connection. Note that HTTP clients are

– 344

– ciphertext not exactly 13 characters in length (including the two salt characters at the beginning) 345

– missing or invalid integer for the &lt;threads&gt; argument. The number of threads requested must 346

be greater than or equal to 1, and less than or equal to 50. 347

• Invalid salt string provided for the crypt command (e.g. not two characters or uses invalid characters) 348

• Invalid salt substring in the ciphertext for the crack command. 349

• Too few or too many arguments 350

• Any other kind of malformed message 351

Provided Libraries 352

libcsse2310a4 353

A split_by_char() function is available to break a line up into multiple parts, e.g. based on spaces. This is 354

similar to the split_line() function from libcsse2310a3 though allows a maximum number of fields to be 355

specified. 356

Several additional library functions have been provided to aid CSSE7231 students in parsing/construction 357

of HTTP requests/responses. The functions in this library are: 358

empty strings (for any field)

char** split_by_char(char* str, char split, unsigned int maxFields); int get_HTTP_request(FILE *f, char **method, char **address,

HttpHeader ***headers, char **body);

char* construct_HTTP_response(int status, char* statusExplanation,

HttpHeader** headers, char* body);

int get_HTTP_response(FILE *f, int* httpStatus, char** statusExplain,

HttpHeader*** headers, char** body);

void free_header(HttpHeader* header);

void free_array_of_headers(HttpHeader** headers);

These functions and the HttpHeader type are declared in /local/courses/csse2310/include/csse2310a4.h 359

on moss and their behaviour is described in man pages on moss – see split_by_char(3), get_HTTP_request(3), 360

and free_header(3). 361

To use these library functions, you will need to add #include &lt;csse2310a4.h&gt; to your code and use the 362

compiler flag -I/local/courses/csse2310/include when compiling your code so that the compiler can find 363

the include file. You will also need to link with the library containing these functions. To do this, use the 364

compiler arguments -L/local/courses/csse2310/lib -lcsse2310a4 365

libcsse2310a3 366

You are also welcome to use the “libcsse2310a3” library from Assignment 3 if you wish. This can be linked with 367

-L/local/courses/csse2310/lib -lcsse2310a3. Note that split_space_not_quote() is not appropriate for 368

use in this assignment – quotes have no particular meaning in the communication protocol for crackserver. 369

Style 370

Your program must follow version 2.3 of the CSSE2310/CSSE7231 C programming style guide available on the 371

course Blackboard site. 372

373

Review the lectures related to network clients, threads and synchronisation and multi-threaded network 374

servers (and HTTP for CSSE7231 students). This assignment builds on all of these concepts. 375

You should test crackclient and crackserver independently using netcat as demonstrated in the 376

lectures. You can also use the provided demo programs demo-crackclient and demo-crackserver. 377

The multithreaded network server example from the lectures can form the basis of crackserver. 379

Use the provided library functions (see above). 380

Consider a dedicated signal handling thread for SIGHUP. pthread_sigmask() can be used to mask signal 381

delivery to threads, and sigwait() can be used in a thread to block until a signal is received. You will 382

need to do some research and experimentation to get this working. Be sure to properly reference any code 383

samples or inspiration you find online or via generative AI such as ChatGPT. 384

Possible Approach 385

Try implementing crackclient first. (The programs are independent so this is not a requirement, but when 386

For crackserver, try writing a simple non-networked cracking program first to ensure you understand 388

the algorithm and use of libcrypt. 389

Once you can do single threaded cracking, work out how to split it across multiple threads. 390

Finally, integrate your cracking algorithm into the multi-threaded network server. 391

Forbidden Functions 392

the assignment. 394

• goto 395

• #pragma 396

• gcc attributes 397

that calls the function. 399

• longjmp() and equivalent functions 400

• system() 401

• mkfifo() or mkfifoat() 402

• fork(), pipe(), popen(), execl(), execvp() and other exec family members. 403

• pthread_cancel() 404

Submission 405

Your submission must include all source and any other required files (in particular you must submit a Makefile). 406

Do not submit compiled files (eg .o, compiled programs) or test files. 407

Your programs (named crackclient and crackserver ) must build on moss.labs.eait.uq.edu.au with: 408

make 409

If you only implement one of the programs then it is acceptable for make to just build that program – and 410

we will only test that program. 411

Hints

-I 412

etc. – see Provided Libraries above): 413

-pedantic -Wall -std=gnu99 414

source files other than .c and .h files as part of the build process – such files will be removed before building 416

your program. 417

If any errors result from the make command (e.g. an executable can not be created) then you will receive 418

Your program must not invoke other programs or use non-standard headers/libraries (besides those we have 421

provided for you to use). 422

Your assignment submission must be committed to your subversion repository under 423

https://source.eait.uq.edu.au/svn/csse2310-sem1-sXXXXXXX/trunk/a4 424

where sXXXXXXX is your moss/UQ login ID. Only files at this top level will be marked so do not put source 425

will not be considered in marking – they will not be checked out of your repository. 427

You must ensure that all files needed to compile and use your assignment (including a Makefile) are commit- 428

ted and within the trunk/a4 directory in your repository (and not within a subdirectory) and not just sitting 429

in your working directory. Do not commit compiled files or binaries. You are strongly encouraged to check out 430

a clean copy for testing purposes – the reptesta4.sh script will do this for you. 431

To submit your assignment, you must run the command 432

2310createzip a4 433

on moss and then submit the resulting zip file on Blackboard (a GradeScope submission link will be made 434

available in the Assessment area on the CSSE2310/7231 Blackboard site) . The zip file will be named 435

sXXXXXXX_csse2310_a4_timestamp.zip 436

where sXXXXXXX is replaced by your moss/UQ login ID and timestamp is replaced by a timestamp indicating 437

the time that the zip file was created. 438

The 2310createzip tool will check out the latest version of your assignment from the Subversion repository, 439

ensure it builds with the command ‘make’, and if so, will create a zip file that contains those files and your 440

of this process in order to check out your submission from your repository. 442

You must not create the zip file using some other mechanism and you must not modify the zip file prior 443

is submitted via GradeScope on Blackboard, and not the time of your last repository commit nor the time of 445

creation of your submission zip file. 446

for details. 449

Note that Gradescope will run the test suite immediately after you submit. When complete you will be 450

able to see the results of the “public” tests. 451

to attend an interview about your assignment and you are unable to adequately respond to questions – see the 454

Student conduct section above. 455

Your programs must be compiled with gcc with at least the following switches (plus applicable options

Provided your code compiles (see above) and does not use any prohibited statements/functions (see above), 457

for partially meeting the functionality requirements. Not all features are of equal difficulty. If your program 460

claim to have implemented it. Reasonable time limits will be applied to all tests. If your program takes longer 462

test. 464

Exact text matching of files and output (stdout and stderr) and communication messages is 465

used for functionality marking. Strict adherence to the formats in this specification is critical to 466

Note that your client and server will be tested independently. 469

3. crackclient correctly handles input from stdin or a job file 474

4. crackclient correctly displays lines received from the server and sends input lines 476

8. crackserver correctly listens for connections and reports the port 481

10. crackserver correctly handles single-threaded crack requests (with at most 484

11. crackserver correctly handles multi-threaded crack requests (with at most 486

12. crackserver correctly handles crypt requests (with at most one client connected 488

17. crackserver correctly implements SIGHUP statistics reporting (including protecting 494

18. (CSSE7231 only) crackserver correctly listens on the port specified by A4_HTTP_PORT 496

crackserver 498

20. (CSSE7231 only) crackserver supports multiple simultaneous HTTP clients and multiple 500

will be covered in multiple categories (12 to 16). 503

Style Marking 504

Style marking is based on the number of style guide violations, i.e. the number of violations of version 2.3 of 505

You should pay particular attention to commenting so that others can understand your code. The marker’s 508

decision with respect to commenting violations is final – it is the marker who has to understand your code. To 509

more than your functionality mark – this prevents the submission of well styled programs which don’t meet at 511

least a minimum level of required functionality. 512

You are encouraged to use the style.sh tool installed on moss to style check your code before submission. 513

This does not check all style requirements, but it will determine your automated style mark (see below). Other 514

elements of the style guide are checked by humans. 515

All .c and .h files in your submission will be subject to style marking. This applies whether they are 516

compiled/linked into your executable or not . 517

.c and/or .h files are unable to be compiled by themselves then your automated style mark will be zero (0). 520

(Automated style marking can only be undertaken on code that compiles. The provided style.sh script checks 521

this for you.) 522

If your code does compile then your automated style mark will be determined as follows: Let 523

• W be the total number of distinct compilation warnings recorded when your .c files are individually built 524

(using the correct compiler arguments) 525

• A be the total number of style violations detected by style.sh when it is run over each of your .c and 526

.h files individually . 527

Your automated style mark S will be 528

S = 5 − (W + A) 529

penalised incorrectly then please bring this to the attention of the course coordinator and your mark can be 532

errors not picked up when you run style.sh on moss. This will not be considered a marking error – it is your 534

responsibility to ensure that all of your code follows the style guide, even if styling errors are not detected 535

in some runs of style.sh. You can check the result of Gradescope style marking soon after your Gradescope 536

submission – when its test suite completes running. 537

and “other”. The meanings of words like appropriate and required are determined by the requirements in the 540

style guide. Note that functions longer than 50 lines will be penalised in the automated style marking. Functions 541

that are also longer than 100 lines will be further penalised here. 542

19. (CSSE7231 only) correctly responds to HTTP requests (including invalid requests)

Mark Description

0 The majority (50%+) of comments present are inappropriate OR there are many required comments missing

0.5 The majority of comments present are appropriate AND the majority of required comments are present

1.0 The vast majority (80%+) of comments present are appropriate AND there are at most a few missing comments

1.5 All or almost all comments present are appropriate AND there are at most a few missing comments

2.0 Almost all comments present are appropriate AND there are no missing comments

2.5 All comments present are appropriate AND there are no missing comments

544

Naming (1 mark) 545

Mark Description

0 At least a few names used are inappropriate

0.5 Almost all names used are appropriate

1.0 All names used are appropriate

546

Mark Description

0 One or more functions is longer than 100 lines of code OR there is more than one global/static variable present inappropriately OR there is a global struct variable present inappropriately OR there are more than a few instances of poor modularity (e.g. repeated code)

0.5 All functions are 100 lines or shorter AND there is at most one inappropriate non-struct global/static variable AND there are at most a few instances of poor modularity

1.0 All functions are 100 lines or shorter AND there are no instances of inappropriate global/static variables AND there is no or very limited use of magic numbers AND there is at most one instance or poor modularity

1.5 All functions are 100 lines or shorter AND there are no instances of inappropriate global/static variables AND there is no use of magic numbers AND there are no instances of poor modularity

548

will be graded according to the following principles: 551

• Appropriate use and frequency of commits (e.g. a single monolithic commit of your entire assignment will 552

yield a score of zero for this section) 553

• Appropriate use of log messages to capture the changes represented by each commit. (Meaningful messages 554

explain briefly what has changed in the commit (e.g. in terms of functionality) and/or why the change 555

has been made and will be usually be more detailed for significant changes.) 556

The standards expected are outlined in the following rubric: 557

Mark

(out of 5) Description

0 Minimal commit history – only one or two commits OR all commit messages are meaningless.

1 Some progressive development evident (three or more commits) AND at least one commit message is meaningful.

2 Progressive development is evident (multiple commits) AND at least half the commit messages are meaningful.

3 Multiple commits that show progressive development of ALL functionality (e.g. no large commits with multiple features in them) AND at least half the commit messages are meaningful.

4 Multiple commits that show progressive development of ALL functionality AND meaningful messages for all but one or two of the commits.

5 Multiple commits that show progressive development of ALL functionality AND meaningful messages for ALL commits.

558

Total Mark 559

Let 560

• F be the functionality mark for your assignment (out of 60 for CSSE2310 students or out of 70 for 561

CSSE7231 students). 562

• S be the automated style mark for your assignment (out of 5). 563

• H be the human style mark for your assignment (out of 5). 564

• C be the SVN commit history mark (out of 5). 565

• V is the scaling factor (0 to 1) determined after interview(s) (if applicable – see the Student Conduct 566

section above) – or 0 if you fail to attend a scheduled interview without having evidence of exceptional 567

circumstances impacting your ability to attend. 568

Your total mark for the assignment will be: 569

M = (F + min{F,S + H} + min{F,C}) × V 570

out of 75 (for CSSE2310 students) or out of 85 (for CSSE7231 students). 571

Pretty code that doesn’t work will not be rewarded! 573

Late Penalties 574

Late penalties will apply as outlined in the course profile. 575

Specification Updates 576

Any errors or omissions discovered in the assignment specification will be added here, and new versions released 577

discussed on the discussion forum or emailed to csse2310@uq.edu.au. 579

580

• Clarified expected update rate of crypt() call count. 582

• Added further examples of invalid arguments to crackserver commands. 583

• Made it clear that even if only one cracking thread is requested then an additional thread must still be 584

created by the client thread. 585

• Clarified that a missing –maxconn argument means no limit on client connections. «««¡ HEAD 586

• Updated crackclient marking criteria to include inability to read from job files. 587

• Clarified that crackclient is only expected to detect EOF on the network socket when it is reading from 588

the network socket. 589

• Clarified meaning of “blank lines” in crackclient input. 590

• Clarified that marking category 5 includes handling EOF on the source of input (rather than stdin 591

specifically). 592

593

• Clarified crackclient marking criteria about handling input. 595

• Clarified argument count for crackserver. 596

• Added marking category for crackserver dictionary errors (and renumbered subsequent marking cate- 597

• Added requirement that crypt requests must be handled in the client thread – no additional thread is to 599

be created for this. 600

• (CSSE7231) Clarified that HTTP clients are not included in statistics. 601

• Clarified that the crackclient examples were not using a server with the default dictionary. 602
