
һ����װgit
    ���أ���װ

��������
    $ git config --global user.name "Your Name"
    $ git config --global user.email "email@example.com"
    
����ע��github
    1.ע��
    2.����ssh��
    git-bash:����Ŀ¼�£�
    ssh-keygen -t rsa -C "jiilii@126.com"
    ��.sshĿ¼�н�id_rsa.pub���ݸ��Ƶ�github��setting������С�
�ġ������汾��
    $ mkdir learngit
    $ cd learngit
    $ pwd
    $ git init

     ��git clone git@github.com:jiilii/learngit.git
            git clone https://github.com/jiilii/learngit.git
�塢����
    ��ʼ��һ��Git�ֿ⣬ʹ��git init���

    ����ļ���Git�ֿ⣬��������
    1.ʹ������git add <file>��ע�⣬�ɷ������ʹ�ã���Ӷ���ļ���ʵ���Ͼ��ǰ��ļ��޸���ӵ��ݴ�����
    git add readme.txt
    git add .
    2.ʹ������git commit -m <message>����ɡ�ʵ���Ͼ��ǰ��ݴ��������������ύ����ǰ��֧��

    ���git status���������ļ����޸Ĺ�����git diff���Բ鿴�޸����ݡ�
    
    �鿴�ύ����ʷ�汾
    git log
    git log --pretty=oneline
    ���˰汾���ѹ��������ļ����¡�
    git reset --hard 1094a
    git reset --hard HEAD~5

    �����޸ģ����ݴ����ָ���������
    git checkout -- readme.txt ��
    git restore -- readme.txt   /   git restore -- .
    
    �汾�ָ����Ӱ汾��ָ����ݴ����͹�����
    git reset --hard HEAD~
    
    ɾ���ļ�
    git rm del.txt
    
����Զ�ֿ̲�
    1.��github�ϴ���learngit�ֿ�
        ����һ��Զ�̿⣬ʹ������
    git remote add origin git@github.com:jiilii/learngit.git
    ��
    git remote add origin https://github.com/jiilii/learngit.git
    
    ��һ������master��֧����������
    git push -u origin master
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    