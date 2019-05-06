# Remote X11

Use any device as a simple **mouse** and **keyboard** to control any computer.

The *controller* device (the used as *touchpad* device) should run any compatible web browser.

The *server* computer should be able to run *Java 8* *.jar* files.

## How to use

Run the *.jar* as:
```
$ java -Dserver.port=9034 -Djava.awt.headless=false -jar target/remotex11-1.0-SNAPSHOT.jar
```

Go to http://server:9034/remotex11.html

## Currently

1. orange button == left mouse button
1. green button == middle mouse button
1. blue button == right mouse button
1. gray vertical bar == mouse wheel
1. light gray canvas == mouse pad
1. bottom text area, write text
1. "Send" button, send text area value
1. "Clear" button, clear text area
