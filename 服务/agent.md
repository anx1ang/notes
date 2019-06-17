# 代理

代理总结，遇到一次加一次

## 0x01 ssh隧道代理

- shell

  参考

  <https://cloud.tencent.com/developer/article/1134323>

```bash
ssh -qtfnN  -D 0.0.0.0:1080 scan@10.10.10.10 -p 22222
# ssh -qtfnN -D ip_listening:port_listening user@agent_ip -p port
ps -ef |grep 1080
# 查看是否成功连接
```

![image-20190618000514877](assets/shell_ssh_agent.jpg)

- xshell

![image-20190618000205412](assets/xshell_ssh_agent.jpg)