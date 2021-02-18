## S3. ����������� ����� ������, ��� ������ � � �����
#### HEAD � ������� ������, tag � ������������� ������, branch � ���������� �� HEAD ������
#### checkout � ����������� �� ����� ��� ������, reset � ����������� � ������ �� ������
#### ����� ��, �� ��� ���� ������, ��������� � �����
1. `git tag` � ������� ������ �����
2. `git tag <tagname>` � ������� ���
3. `git branch` � ������� ������ ��������� �����
4. `git branch -av` � ������� ������ ��������� � ��������� �����
5. `git branch <branchname>` � ������� �����
6. `git branch -d <branchname>` � ������� �����
7. `git checkout <commit>` ��� `git switch --detach <commit|branch>` � ����������� HEAD �� ������, ������ ��������� detached HEAD
8. `git checkout <branch>`��� `git switch <branch>` � ����������� HEAD �� �����
9. `git checkout -b <new_branch>` ��� `git switch -c <new_branch>` � ������� ����� � ������� �� ���
10. `git reset --hard <commit>` � ����������� HEAD � ������� ����� �� `<commit>`