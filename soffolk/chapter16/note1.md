Rails 里面集成了邮件功能，你可以很简单的用来发送邮件和接受邮件。


## 发送配置

默认使用 sendmail 来发送邮件，一般的linux主机上都会天然有这个命令：
/usr/bin/sendmail

如果没有，你可以使用 smtp 来配置一个外部邮件服务器。

[一些 stmp 邮件配置](https://gist.github.com/lidashuang/4371386)

*注意，qq 个人邮件需要自己开启 stmp 功能才可以用*

## 测试

[email_spec](https://github.com/bmabey/email-spec/) 提供了在 Rspec，
Minitest 以及 cucumber 中里面测试邮件，包括发送人，收件人，cc，bcc，主题，内容，头等等。

## 接受邮件

你甚至可以用 Rails
处理邮件，在这之前，你需要配置你的服务器，确保将邮件转发到你的 Rails
app 。

然后，你需要定义一个 UserMailer 的 receive 的方法，so
，你就可以将邮件存下来或者做一些其它有意思的东西。
