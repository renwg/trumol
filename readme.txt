1��windowsƽ̨���ص�ַ
   http://msysgit.github.io/

2����װ��ɺ󣬻���Ҫ���һ�����ã������������룺
   $ git config --global user.name "trumol"
   $ git config --global user.email "475609041@qq.com"

   //��ΪGit�Ƿֲ�ʽ�汾����ϵͳ�����ԣ�ÿ�������������Ա����ţ�������ֺ�Email��ַ��
   //git config�����--global���������������������ʾ����̨���������е�Git�ֿⶼ��ʹ��������ã�

3�������汾��
   3.1 ��һ����ѡ��һ�����ʵĵط�������һ����Ŀ¼��
   $ mkdir E:/repository
   $ cd E:/repository
   $ pwd
    E/repository

   3.2 �ڶ�����ͨ��git init��������Ŀ¼���Git���Թ���Ĳֿ⣺
   $ git init

4����һ���ļ��ŵ�Git�ֿ�ֻ��Ҫ������
   4.1 ��һ����������git add����Git�����ļ���ӵ��ֿ⣺
   $ git add readme.txt

   4.2 �ڶ�����������git commit����Git�����ļ��ύ���ֿ⣺
   $ git commit -m "wrote a readme file"

5������git status��������

6���鿴��ʷ��¼
   ��Git�У�������git log����鿴��
   $ git log --pretty=oneline

7���汾����
   ����Ҫ�ѵ�ǰ�汾��append GPL�����˵���һ���汾��add distributed�����Ϳ���ʹ��git reset���
   ��Git�У���HEAD��ʾ��ǰ�汾,
   ��һ���汾����HEAD^������һ���汾����HEAD^^����Ȼ����100���汾д100��^�Ƚ�������������������д��HEAD~100
   $ git reset --hard HEAD^

8���ָ���ָ���汾 git reset --hard commit_id
   $ git reset --hard cb926e7

9����git reflog�鿴������ʷ���Ա�ȷ��Ҫ�ص�δ�����ĸ��汾��
   $ git reflog

10����git log���Բ鿴�ύ��ʷ���Ա�ȷ��Ҫ���˵��ĸ��汾��
   $ git log --pretty=oneline


https://github.com/twbs/bootstrap
http://www.liaoxuefeng.com/wiki/0013739516305929606dd18361248578c67b8067c8c017b000/001374829472990293f16b45df14f35b94b3e8a026220c5000
  
