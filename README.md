# andre

Add this to your hosts file (`/etc/hosts`)

```
127.0.0.1       andre
127.0.0.1       xn--andr-epa
```

Add this to your `~/.bashrc`

```
alias andre="./manage.py runserver 0.0.0.0:3000"
```

Or if you're using fish, `~/.config/fish/config.fish`

```
function andre
    ./manage.py runserver 0.0.0.0:3000
end
```

Now you can start a django project via `andre` instead of `./manage.py runserver`.

Also you can pull up your django site at <http://andré:3000/> (<http://andre:3000/> works as well)
