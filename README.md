我是光年实验室高级招聘经理。
我在github上访问了你的开源项目，你的代码超赞。你最近有没有在看工作机会，我们在招软件开发工程师，拉钩和BOSS等招聘网站也发布了相关岗位，有公司和职位的详细信息。
我们公司在杭州，业务主要做流量增长，是很多大型互联网公司的流量顾问。公司弹性工作制，福利齐全，发展潜力大，良好的办公环境和学习氛围。
公司官网是http://www.gnlab.com,公司地址是杭州市西湖区古墩路紫金广场B座，若你感兴趣，欢迎与我联系，
电话是0571-88839161，手机号：18668131388，微信号：echo 'bGhsaGxoMTEyNAo='|base64 -D ,静待佳音。如有打扰，还请见谅，祝生活愉快工作顺利。

git + hub = github
==================

hub is a command line tool that wraps `git` in order to extend it with extra
features and commands that make working with GitHub easier.

~~~ sh
$ hub clone rtomayko/tilt

# expands to:
$ git clone git://github.com/rtomayko/tilt.git
~~~

hub is best aliased as `git`, so you can type `$ git <command>` in the shell and
get all the usual `hub` features. See "Aliasing" below.


Installation
------------

Dependencies:

* **git 1.7.3** or newer

#### Homebrew

`hub` can be installed through Homebrew:

~~~ sh
$ brew install hub
$ hub version
git version 1.7.6
hub version 2.2.0
~~~

#### Standalone

`hub` can be easily installed as an executable. Download the latest
[compiled binaries](https://github.com/github/hub/releases) and put it anywhere
in your executable path.

#### Source

To install `hub` from source, you need to have a [Go development environment](http://golang.org/doc/install):

~~~ sh
$ git clone https://github.com/github/hub.git
$ cd hub
# Assuming `~/bin` is in your PATH:
$ ./script/build -o ~/bin/hub
~~~

Aliasing
--------

Using hub feels best when it's aliased as `git`. This is not dangerous; your
_normal git commands will all work_. hub merely adds some sugar.

`hub alias` displays instructions for the current shell. With the `-s` flag, it
outputs a script suitable for `eval`.

You should place this command in your `.bash_profile` or other startup script:

~~~ sh
eval "$(hub alias -s)"
~~~

### Shell tab-completion

hub repository contains tab-completion scripts for bash and zsh. These scripts
complement existing completion scripts that ship with git.

[Installation instructions](etc)

* [hub bash completion](https://github.com/github/hub/blob/master/etc/hub.bash_completion.sh)
* [hub zsh completion](https://github.com/github/hub/blob/master/etc/hub.zsh_completion)

Meta
----

* Home: <https://github.com/github/hub>
* Bugs: <https://github.com/github/hub/issues>
* Authors: <https://github.com/github/hub/contributors>

### Prior art

These projects also aim to either improve git or make interacting with
GitHub simpler:

* [eg](http://www.gnome.org/~newren/eg/)
* [github-gem](https://github.com/defunkt/github-gem)
