## Chapter 01 - _New Born Baby_

There you are, nice to meet you again. Ready to get some **basic** stuff here aren't you?
Here we go..

Having an updated nano from _brew_, will get you many `*.nanorc` in /usr/local/share/nano/
>_So, what's about it?_

Well, it may be look smarter if you type something and the text change it's color, right?
It's called _syntax highlighting_

>_Can you repeat?_

Um.. Okay, it's not basic.. _(damn, they'll figure out how dumb I am now...)_

Okay, back to the basic shall we?


#### A. Open nano editor
   - Open terminal, then type **nano**

![Nano-01](https://user-images.githubusercontent.com/85201626/180642708-44b96556-627e-4695-ad21-eafe1ec18820.jpeg)

#### B. Where's the manual?
  - Press **F1 key** or **^G** (Ctrl + G)
>_Okay, now I see some of these:_ " Meta-key sequences are notated with 'M-' " _What is Meta-key?_

Meta-key is an **`Esc`** key. Example: if you want to **undo**, and you see in the help mode is **`M-U`**, so you press **`Esc+U`**

The rest can be read at the help text (manual).

Oh, there's more, in the manual there is some of these: `^G     (F1)     Display this help text`

Means besides pressing **`Ctrl+G`** you can invoke command using **`F1`** too!

I usually saving my work using **`F3`**, and close the document using **`F2`**

>Hell no! What else? Can i use Cmd+C to copy and Cmd+V to paste?

Well, sort of.. Do you mean "How to copy and paste in nano"?

#### C. Copy and Paste in nano editor (and cutting)
##### Copy and Paste
There are 2 ways to do it --_for I don't know what else, Im still dummy you remember?_
  1. The primitive way: You can copy and paste using regular hotkey, _IF_, you **`block`** _(click and drag)_ the text on the terminal or other app **`using mouse`**, copy it using **`Cmd+C`** and paste it using **`Cmd+V`**.
  2. The coder way: hold **`SHIFT`**, press **`right arrow`** to block some text inside nano, then press **`Esc+6`** to copy, last press **`Ctrl+U`** to paste.

##### Cut and Paste
Well, I'd love to cut in nano. Just press **`Ctrl+K`** and wow! It's cutting a whole line! I'm amazed at the first time using it.

Cut

Cut more

Cut few more times, many lines cutted

and.. where's the text gone? --Well, its in the _cutbuffer_. Same when you copy using **`Alt+6`**, the copied text also in the _cutbuffer_.

Paste it using **`Ctrl+U`**. Done.

>Okay, I get it. Now, if I want to make some file not in current directory, do I have to _cd_ to the target directory first?

(Ow, what a question, are you advance user or what? _Damn_, I have to _Google_ it now..)

Good questions, answer is: you don't have to change directory --thanks _Google_.

You can make a file with 3 ways --_again, for I don't know what else..._
   1. `nano filename`
      - create "filename" in current directory. You can spesify file extension too, like: filename.txt, filename.sh, etc
   2. `nano /Document/FolderA/FolderAa/FolderAa1/filename`
      - create "filename" in /Document/FolderA/FolderAa/FolderAa1/ directory.
   3. `nano` --then `drag a desired folder from Finder to the terminal`, then type the desired "filename"
      - create "filename" in folder you've dragged to the terminal

#### D. Cheatshit Please!
Okay, impatient is good when learning...
Here are few shortcuts I used the most:
|**You want to...**|**Nano way**|**Other way**|
|---|---|---|
|Help! (manuals)              |**F1** or **Ctrl+G**          |                |
|Select text (marking)        |**Hold shift+arrow key**  |Click and drag using mouse   |
|Select text cooler way       |**Esc+A** or **Ctrl+6**       |Click and drag using mouse   |
|Cancel operation             |**Ctrl+C**                |                             |
|Copy blocked text            |**Esc+6**                 |Cmd+C                        |
|Cut blocked text             |**Ctrl+K** or **F9**          |~~Cmd+X~~                    |
|Cut a text line              |**Ctrl+K** or **F9** w/out blocking |cannot                       |
|Paste (works with copy/cut)  |**Ctrl+U** or **F10**         |Cmd+V                        |
|Find a text                  |**Ctrl+W**                |Cmd+F                        |
|Find next                    |**Alt+W** or **F6**           |Cmd+G                        |
|Find previous                |**Alt+Q**                 |Cmd+Shift+G                  |
|Go to line/collumn           |**Esc+G**                 |                             |
|Replace text                 |Ctrl+\ or **Esc+R**       |                             |
|Undo                         |**Esc+U**                 |~~Cmd+Z~~                    |
|Redo                         |**Esc+E**                |~~Cmd+Shift+Z~~              |
|Comment (add # before text)  |Esc+3 block some text line for multi commenting | Manually add # before text  |
|Insert text from other file  |**Ctrl+R**                |Open other file with text editor, copy it, paste it... |
|Save file                    |**F3** or **Ctrl+O**          |~~Cmd+S~~ (is save terminal output)...       |
|Exit (with or w/out saving)  |**F2** or **Ctrl+X**          |~~Cmd+W or Cmd+Q~~ (will screwed up your work)...       |
|Auto complete<sup>*</sup>    |**Esc+U**                 |                            |
|Execute terminal command<sup>**</sup>     |**Ctrl+T**   |                             |

<sup>*</sup> Must enable it in nanorc

<sup>**</sup> Hey! What is it? --well I'll cover it in the next chapter 👌
