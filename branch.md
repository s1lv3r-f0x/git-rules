## S3. ����������� ����� ������, ��� ������ � � �����
#### HEAD � ������� ������, tag � ������������� ������, branch � ���������� �� HEAD ������
#### checkout � ����������� �� ����� ��� ������, reset � ����������� � ������ �� ������
#### ����� ��, �� ��� ���� ������, ��������� � �����
- `git tag` � ������� ������ �����
- `git tag <tagname>` � ������� ���
- `git branch` � ������� ������ ��������� �����
- `git branch -av` � ������� ������ ��������� � ��������� �����
- `git branch <branchname>` � ������� �����
- `git branch -d <branchname>` � ������� �����
- `git checkout <commit>` ��� `git switch --detach <commit>` � ����������� HEAD �� ������, ������ ��������� detached HEAD
- `git checkout <branch>`��� `git switch <branch>` � ����������� HEAD �� �����
- `git checkout -b <new_branch>` ��� `git switch -c <new_branch>` � ������� ����� � ������� �� ���
- `git reset --hard <commit>` � ����������� HEAD � ������� ����� �� `<commit>`
- `git reflog show <ref>` � �������� ��� �������� �� �������
- `git reflog` = `git reflog show HEAD` � �������� ��� �������� � HEAD
- `git gc` � ������� �������� ����� � �������������� ��������� �����������