node_authlink
=============

原版本见https://drupal.org/project/node_authlink
=============

该模块可以实现：
给Node一个密钥，携带正确的密钥任何匿名用户都可以修改，删除、编辑该node
=============

新增功能：
给Node的url增加query,如
http://localhost/node/3?authkey=d9d65ab58d507f3fa3451a7c6075013bd1901492a6d262dc5805ef5e9ea99c95，当然这个authkey只有管理员可以看到.
