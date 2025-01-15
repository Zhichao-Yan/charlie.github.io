# Chirpy Starter

[![Gem Version](https://img.shields.io/gem/v/jekyll-theme-chirpy)][gem]&nbsp;
[![GitHub license](https://img.shields.io/github/license/cotes2020/chirpy-starter.svg?color=blue)][mit]


## Prerequisites
### What's Gems
> Gems are code you can include in Ruby projects. Gems package specific functionality. You can share gems across multiple projects or with other people
### What's Gemfile
> A Gemfile is a list of gems used by your site. Every Jekyll site has a Gemfile in the main folder.
### What's bundle
* bundle is a gem written in Ruby
* bundle installs all gems in your Gemfile
* bundle ensures you’re running the same version of Jekyll and its plugins across different environments.
### bundle command
1. `bundle install`
根据项目根目录下的 Gemfile 文件中列出的 gem 依赖，自动下载并安装这些 gem 及其依赖的其他 gem,并且生成一个 Gemfile.lock 文件,确保在不同环境中安装的 gem 版本一致
2. `bundle exec jekyll serve`
bundle exec 是一个非常有用的命令，它确保在执行命令时使用的是 Gemfile 中指定的 gem 版本，而不是全局安装的 gem 版本。通过 Gemfile.lock 文件，bundle exec 确保每次执行命令时使用的 gem 版本与项目依赖的版本一致。这有助于避免版本冲突，确保项目的一致性和可复现性。
e.g. 这里使用bundle exec执行jekyll serve,确保使用的是项目环境要求的Jekyll版本
3. `bundle info --path jekyll-theme-chirpy`
定位gem包的路径
4. `bundle info jekyll-theme-chirpy`
返回某个gem包的信息

### What's Jekyll
* Jekyll is written in Ruby
* Jekyll is a gem

### Functionality of Jekyll
> Jekyll is a static site generator. It takes text written in your favorite markup language and uses layouts to create a static website

## Environment for Chirpy theme

Follow the instructions in the [Jekyll Docs](https://jekyllrb.com/docs/installation/) to complete the installation of the basic environment. [Git](https://git-scm.com/) also needs to be installed.



## Installation of Chirpy theme

Sign in to GitHub and [**use this template**][use-template] to generate a brand new repository and name it
`USERNAME.github.io`, where `USERNAME` represents your GitHub username.

Then clone it to your local machine and run:
```console
$ bundle
```

## Usage

Please see the [theme's docs](https://github.com/cotes2020/jekyll-theme-chirpy#documentation).

## preview
`bundle exec jekyll s`
or
`bundle exec jekyll s --incremental`

## reference
* [blog](https://chirpy.cotes.page/posts/write-a-new-post/)  
* [jekyll-compose](https://github.com/jekyll/jekyll-compose)

## command
1. `bundle exec jekyll post "My New Post"`
2. `bundle exec jekyll draft "My new draft"`
3. `bundle exec jekyll publish _drafts/my-new-draft.md`
4. `bundle exec jekyll unpublish _posts/2014-01-24-my-new-draft.md`

## License

This work is published under [MIT][mit] License.

[gem]: https://rubygems.org/gems/jekyll-theme-chirpy
[chirpy]: https://github.com/cotes2020/jekyll-theme-chirpy/
[use-template]: https://github.com/cotes2020/chirpy-starter/generate
[CD]: https://en.wikipedia.org/wiki/Continuous_deployment
[mit]: https://github.com/cotes2020/chirpy-starter/blob/master/LICENSE
