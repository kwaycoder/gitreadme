repository

�����汾��
mkdir v0.0.1
cd v0.0.1
pwd
git init

���ļ���ӵ����زֿ�
/**û����ʾ��������
git add readme.txt  

���ļ��ύ��Զ�ֿ̲�
git commit -m '�������ļ���ӵ�Զ�ֿ̲�'

�鿴��ǰ���ؿ��״̬
git status

�鿴�ı��仯
git diff <file>

�鿴���а汾
git log 
�� git log --pretty=oneline
�� 

���˰汾
/**������һ���汾
git reset --hard HEAD^
/**�������������汾
git reset --hard HEAD^^
/**����ָ���汾��
git reset --hard 1094a

������ dir
�汾�� .git
	�ݴ���
	master
	head
git add ->�ݴ���
git commit ->��֧


�����޸�
git checkout -- [file]

ɾ���ļ�
git rm readme.txt
git commit -m 'remove readme.txt'

github��Կ
C:\Users\hcjijin\.ssh

�ϴ�Զ�̷���������
��Ҫ��pull��push
pull����refusing to merge unrelated histories
ԭ��
����������������Ҫԭ�������ڱ��زֿ��Զ�ֿ̲�ʵ�����Ƕ����������ֿ⡣������֮ǰ��ֱ��clone�ķ�ʽ�ڱ��ؽ�����Զ��github�ֿ�Ŀ�¡���زֿ�Ͳ������������ˡ�
$git pull origin master --allow-unrelated-histories