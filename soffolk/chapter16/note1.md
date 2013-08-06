Rails 里面集成了邮件功能，你可以很简单的用来发送邮件和接受邮件。


## 发送配置

默认使用 sendmail 来发送邮件，一般的linux主机上都会天然有这个命令：
/usr/bin/sendmail

如果没有，你可以使用 smtp 来配置一个外部邮件服务器。

## 测试

[email_spec](https://github.com/bmabey/email-spec/) 提供了在 Rspec，
Minitest 以及 cucumber 中里面测试邮件，包括发送人，收件人，cc，bcc，主题，内容，头等等。
