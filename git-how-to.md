# Работа с Git (Linux)

1. Установка git

```bash
sudo apt-install git
```

2. Создание SSH-ключ

```bash
ssh-keygen -t ed25519 -C "ваш_email@example.com"
cat ~/.ssh/id_ed25519.pub
```

3. Добавить ключ в GitHub

4. Клонирование репозитория

```bash
git clone git@github.com:username/repo.git
```
