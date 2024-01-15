## Install rbenv

Distro dependent

## Install ruby through rbenv

```
rbenv -l
rbenv install <ver>
```

## Add rbenv to .bashrc

```
if [ -x /usr/bin/rbenv ]; then
    eval "$(rbenv init - bash)"
fi
```

## Set ruby version for project

```
cd <project dir>
rbenv local <ver>
```

## Install bundler

```
gem install bundler
```

## Install additional project gems

```
bundle install
```

