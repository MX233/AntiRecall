#AntiRecall �����ز��

����һ������[`mirai`](https://github.com/mamoe/mirai) �����˿�ܵĲ��

��������ģ��? ��mirai�ϰ�װ��������м����ü���ʵ��

![image](images/show.png)

#һ��Ҫ�ȿ���README

##���������
- ��ȡ�����ص���Ϣ
- �����ƽ�

##ǰ�ò��
- [chat-command](https://github.com/project-mirai/chat-command)

##ָ��
**ǰ׺һ���� `/`**

| ָ��                       | ����           | ʾ��                                   |
|:-------------------------|:-------------|:-------------------------------------|
| `ar` `eb` `<true/false>` | `���ÿ�����ر�`    | ar en true                           |
| `ar` `ca`  `<time>`      | `������Ϣ����ʱ��`   | ar ca 30                             |
| `ar` `fm`  `<text>`      | `����ת����Ϣ����Ϣ��` | ${sender}������һ��${type}��Ϣ:\n${message} |
| `ar` `reload`            | `��������`       | -                                    |

##�״�ʹ��
��ʹ��[Mirai Console Backend - Permissions](https://docs.mirai.mamoe.net/console/Permissions.html)
����Ȩ��

###���һ����������
> ���������߷�����Ϣ��ᱻ�����ת��
```
perm add m<Ⱥ��>.* top.cutestar.antirecall:monitored
//һ��ʾ��:perm add m123456789.* top.cutestar.antirecall:monitored
```
��������Ⱥ
```
perm add m* top.cutestar.antirecall:monitored
```

###���һ����Ϣ������
> ������ѡ�����͵���Ϣʱ������Ϣ�ᱻת������Ϣ������
```
perm add <�������ID> top.cutestar.antirecall:receiver
//һ��ת�������ѵ�ʾ��:perm add f123456789 top.cutestar.antirecall:receiver
//һ��ת����Ⱥ��ʾ��:perm add g123456789 top.cutestar.antirecall:receiver
```

###�������ʹ��Ȩ��
```
perm add u<qq��> top.cutestar.antirecall:command.ar
```

����Ȩ�޺���ʹ��`ar reload`����

�û�QQȺ:[`589775128`](https://jq.qq.com/?_wv=1027&k=dNKLKgIs)