[Django モジュール一覧](https://docs.djangoproject.com/ja/3.2/py-modindex/)

# 認証機能の実装

## カスタムユーザーを作成
[参照](https://dev-yakuza.posstree.com/django/custom-user-model/)
accounts/models.py
```python
# Import
from django.db import models
from django.contrib.auth.models import AbstractBaseUser, PermissionsMixin, BaseUserManager
from uuid import uuid4
from django.utils import timezone
```
