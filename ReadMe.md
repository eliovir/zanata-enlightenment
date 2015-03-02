I18N repository to manage Enlightenment translations in Zanata.

# Add a project to manage

Edit `update.sh`.

# Update Gettext templates

`./update.sh`

# Push Gettext templates to Zanata

## How to install zanata-cli

```
cd ~/bin
wget http://wwwftp.ciril.fr/pub/apache//ant/ivy/2.4.0/apache-ivy-2.4.0-bin.tar.gz
tar zxvf apache-ivy-2.4.0-bin.tar.gz
export IVY_JAR=~/bin/apache-ivy-2.4.0/ivy-2.4.0.jar
wget https://raw.github.com/zanata/zanata-client-ivy/master/zanata-cli
chmod 755 zanata-cli
```

## Push

`zanata-cli push`
