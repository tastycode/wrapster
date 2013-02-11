Wrapster
=======

Ever get tired of specifying long lists of environment variables? 

![sadcat](http://i.imgur.com/fYrK5K2.png "Sad Cat")

Well, tire no more! Store your environment variables in a yaml or json
file. Then pass them to Wrapster.

    $ echo "foo: bar" > test.yml

    # execute command "env" with variables in test.yml
    $ wrapster test.yml env | grep foo

Wrapster supports json and yaml. This started out as a gist, but I guess
I will make it a repo even without tests. 

Contributers are welcome, I move around projects quite a bit.
