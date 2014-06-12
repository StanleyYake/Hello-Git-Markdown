hello-world
===========
[格式编辑器](https://www.zybuluo.com/mdeditor)

[markdown-basics](https://help.github.com/articles/markdown-basics)

[GitHub Flavored Markdown](https://help.github.com/articles/github-flavored-markdown)

just a repository (project)
When you create a branch, you’re making a copy of the original branch as it was at that point in time (like a photo snapshot). If the original branch changes while you’re working on your new branch, no worries, you can always pull in those updates.

#####井号为大标题，一个、两个、三个等等（最多6个）



#####代码段开头4个空格

    printf("Hello Yake!");
   
 
##### 代码段放在```中（1旁边的那个键）
```c 
int main(){
 printf("Hello Yake!");
 return 0;
    }
```


    
#####**引用名言冒号,下一行用>号**
In the words of Abraham Lincoln:
> Pardon my french


#####**粗体字**
**This text will be bold**粗体（放在****之间）

*This text will be italic*斜体(放在**之间)


#####**编号1（杠或星号）**

>-我

>-你

>-他


1. Item 1
2. Item 2
3. Item 3


<ol>
  <li>first item</li>
  <li>second item      <!-- Look, the closing </li> tag is not placed here! -->
    <ul>
      <li>second item first subitem</li>
      <li>second item second subitem</li>
      <li>second item third subitem</li>
    </ul>
  </li>                <!-- Here is the closing </li> tag -->
  <li>third item</li>
</ol>


#####**编号2（从7开始）**
<ol start="7">
  <li>first item</li>
  <li>second item</li>
  <lI>third item</li>
</ol>

~~Mistaken text.~~



#####任务进度    
- [ ] a bigger project先是杠空格，然后方括号
  - [x] first subtask #1234 learning basic markdown完成了的方括号里放x
  - [ ] follow up subtask #4321
  - [ ] final subtask cc @mention
- [ ] a separate task



引用
* SHA: a5c3785ed8d6a35868bc169f07e40e889087fd2e
* User@SHA: jlord@a5c3785ed8d6a35868bc169f07e40e889087fd2e
* User/Repository@SHA: jlord/sheetsee.js@a5c3785ed8d6a35868bc169f07e40e889087fd2e
* #Num: #26
* User#Num: jlord#26
* User/Repository#Num: jlord/sheetsee.js#26 



| Left-Aligned  | Center Aligned  | Right Aligned |
| :------------ |:---------------:| -----:|
| col 3 is      | some wordy text | $1600 |
| col 2 is      | centered        |   $12 |
| zebra stripes | are neat        |    $1 |

