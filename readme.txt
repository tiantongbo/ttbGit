git config --global user.name 'yourname'
git config --global user.email 'email'

mkdir dir  ����Ŀ¼
cd ����Ŀ¼
pwd ��ʾ��ǰĿ¼
git init  ��ʼ��git�汾�ֿ�
git add   ��ӵ�������,�ݴ���
git commit -m   ��ӵ����زֿ�
git status   �鿴���
git ��Ϊ������,�ݴ���,���زֿ�,�����й�
HEAD^ ������һ���汾HEAD^^������2���汾,HEAD~1002
git reset --hard HEAD ���˵�һ���汾
git log       �鿴��־
git reflog        �鿴��־ 
git diff  HEAD -- readme.txt        �鿴��汾�������
 git checkout -- readme.txt         �ѹ����������ݳ���
git reset HEAD readme.txt           ���ݴ����޸�   
 
ssh-keygen -t rsa -C 'yourEmail'      ����id_ssh  id_ssh_pub
git remote add origin                  ����Զ�̿�
git push -u origin master             ��Զ�̿�����

�鿴��֧��git branch

������֧��git branch <name>

�л���֧��git checkout <name>

����+�л���֧��git checkout -b <name>

�ϲ�ĳ��֧����ǰ��֧��git merge <name>

ɾ����֧��git branch -d <name>
dsadasdadqad    mastr