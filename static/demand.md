1. ���û���أ���ȡ�û�ac��Ŀ���ղ���Ŀ�����ڳ���������Ŀ��
����  
��  
�ɹ���Ӧ��  
```
{
  "status": 200,
  "message": "",
  "data": {
    "star":[1001,1002,1003,1004,1005],
    "ac":[1001,1002,1005],
    "on":[1003,1004]
  }
}
```
ʧ����Ӧ��  
��
***
2. ��ȡ���ڵı����б�  
����С��queryright�����������(status:206)��
```
{
  "queryleft": 1,
  "queryright": 4
}
```
�ɹ���Ӧ��  
``` 
{
  "status": 200,
  "message": "",
  "data": [{
    "contestTitle": "���±���",
    "contestContent": "���¼��",
    "start": "��ʼʱ���",
    "end": "����ʱ���",
    "contestID": "����id������ʹ��"
  }, {
    "contestTitle": "ACM/ICPC 2018",
    "contestContent": "ACM/ICPC 2018",
    "start": "2012-01-01T12:00:00Z",
    "end": "2012-01-01T12:00:00Z",
    "contestID": "2"
  }, {
    "contestTitle": "ACM/ICPC 2018",
    "contestContent": "ACM/ICPC 2018",
    "start": "2012-01-01T12:00:00Z",
    "end": "2012-01-01T12:00:00Z",
    "contestID": "3"
  }, {
    "contestTitle": "ACM/ICPC 2018",
    "contestContent": "ACM/ICPC 2018",
    "start": "2012-01-01T12:00:00Z",
    "end": "2012-01-01T12:00:00Z",
    "contestID": "4"
  }]
}
```
ʧ����Ӧ��    
��
***
3. ��ȡ���ڵ���������  
����С��queryright�����������(��queryleft����������)(status:206)��
```
{
  "queryleft": 1,
  "queryright": 10
}
```
�ɹ���Ӧ��
```
{
  "status": 200,
  "message": "",
  "data": [{
      "id": "����item��id",
      "imgurl": "�û�ͷ��",
      "imgalt":"ͷ��������֣�һ��Ϊ�������û�",
      "node": "�������ڰ��",
      "title":"���۵ı���",
      "timestamp": "���۷����ʱ���2012-01-01T12:00:00Z",
      "laststamp": "���ظ�ʱ���2012-01-01T12:00:00Z",
      "sponsor":"���۷�����",
      "terminator":"���ظ����û�//̫���ӵĻ�ȥ�������"
    },
    {
        "id": "1",
        "imgurl": "https://static.hdslb.com/images/member/noface.gif",
        "imgalt":"sakura",
        "node": "no",
        "title":"̩���ܵ������Ƕ��٣�",
        "timestamp": "2012-01-01T12:00:00Z",
        "laststamp": "���ظ�ʱ���2012-01-01T12:00:00Z",
        "sponsor":"sakura",
        "terminator":"̩����"
    },
    {
        "id": "2",
        "imgurl": "https://static.hdslb.com/images/member/noface.gif",
        "imgalt":"sakura",
        "node": "no",
        "title":"̩���ܵ�����Ƕ��٣�",
        "timestamp": "2012-01-01T12:00:00Z",
        "laststamp": "���ظ�ʱ���2012-01-01T12:00:00Z",
        "sponsor":"sakura",
        "terminator":"̩����"
    }
  ]
}
```
ʧ����Ӧ��   
��
***
4. ������ӵ���Ŀ
����С��queryright�����������(status:206)��
```
{
  "queryleft": 1,
  "queryright": 4
}
```
�ɹ���Ӧ��
```
{
  "status": 200,
  "messages": "",
  "data": [{
      "problemsID": "1001",
      "problemsName": "A+B Problem",
      "problemsRatio": 0.96
    },
    {
      "problemsID": "1002",
      "problemsName": "A*B Problem",
      "problemsRatio": 0.90
    },
    {
      "problemsID": "1003",
      "problemsName": "A/B Problem",
      "problemsRatio": 0.85
    }, {
      "problemsID": "1004",
      "problemsName": "A+B Problem",
      "problemsRatio": 0.96
    }
  ]
}
```
ʧ����Ӧ��
��
***
5. ���ڱ���ҳ���rank�������������û�����  
����  
```
{
  "id": 1,//����id
  "queryleft": 1,
  "queryright": 5
}
```
�ɹ���Ӧ��  
```
{
  "status": 200,
  "message": "",
  "data":[
    {
      "nickname": "�û�nick",
      "aclist": [0,1,2,3,4,5,6]
    },{
      "nickname": "�û�nick",
      "aclist": [0,1,2,3,4,5,6]
    },{
      "nickname": "�û�nick",
      "aclist": [0,1,2,3,4,5,6]
    },{
      "nickname": "�û�nick",
      "aclist": [0,1,2,3,4,5,6]
    },{
      "nickname": "�û�nick",
      "aclist": [0,1,2,3,4,5,6]
    },]
}
```
ʧ����Ӧ�� 
��
***
6. ��ȡ��������  
����  
```
{
  "id": 1//����id
}
```
�ɹ���Ӧ�� 
```
{
  "status": 200,
  "message": "",
  "data": {
    "sum": 10
  }
}
```
ʧ����Ӧ��  
��

