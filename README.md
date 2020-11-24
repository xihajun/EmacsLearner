# EmacsLearner
Learning how to use emacs to improve the productive forces!

[online emacs](http://www.ymacs.org/demo/)
看丹和很多人用emacs，我觉得自己也不能落后，虽然我的目标都是一日曝十日寒 :(

配置emacs使我头疼，看了一些攻略，看来应该先使用[高手](http://pages.sachachua.com/.emacs.d/Sacha.html#org332b2fd)的配置环境，熟悉一下他们的快捷方式之后继续学习可能会方便些。

***
- [ ] Be good at emacs
- [x] Install emacs in hutchison's computer and use it as a daily basis (due by 2020. Aug 10th)
  - 现在知道如何在Linux终端打开emacs了
  - `dnf install emacs`
  - `emacs filename`
  - 其实貌似和vi差不多

- [x] 2020.8.11 Change a theme
  - [how to do that](http://ergoemacs.org/emacs/emacs_playing_with_color_theme.html)
- [x] Go though the tutorial (30 mins)

## online resources
- [Org-mode](https://www.youtube.com/watch?v=bzZ09dAbLEE)
## spacemacs in terminal
I think the terminal is more useful this time than a GUI. Maybe let try to get use to do it in the terminal.
- install spacemacs
- 重新下载spacemacs出现了难以解决的问题，为什么终端和GUI要下载两遍，为什么MacBook的各种版本那么复杂
- 各种报错头大，是不是要去学计算机组成原理
## 浏览器
浏览器在MacBook下还是使用Safari比较好，首先这个touch bar如果使用chrome就会被阉割，但是不知道火狐浏览器会是什么样的效果。

那么要在MacBook下愉快地使用，我们需要下载几个插件：
- Vimari 
  - 可以直接在app商店上找到
  - 使用快捷键对Safari网页进行操作
- Pocket
  - 可以打包网页，另外还有印象笔记，Instapaper等
- 待续，为了用emacs加油

## Tips
- [多行编辑](http://www.langdebuqing.com/emacs%20notebook/emacs%20多行编辑.html)
  - c-x r k 删除
<details><summary>M-n M-p: half page roll</summary>
<p>
  
  ```el
  (defun scroll-half-page-down ()
    "scroll down half the page"
    (interactive)
    (scroll-down (/ (window-body-height) 2)))
  
  (defun scroll-half-page-up ()
    "scroll up half the page"
    (interactive)
    (scroll-up (/ (window-body-height) 2)))

  (global-set-key "\M-n" 'scroll-half-page-up)
  (global-set-key "\M-p" 'scroll-half-page-down)
  ```
</p>
</details>

## Games 
When I learned some vim command from [MIT lecture](https://www.youtube.com/watch?v=a6Q8Na575qc), the lecture mentioned VIMGolf - a vim game to improve your editor skill. I found simliar thing for emacs

- From: [how to be efficient in emacs](https://www.reddit.com/r/emacs/comments/47p4sw/how_to_be_extremely_efficient_in_emacs/) I found nothing
- From: Google I found [Games for emacs](https://www.masteringemacs.org/article/fun-games-in-emacs)
