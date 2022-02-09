# test
example of test with bash


If expect is not installed on our system, we might need to install it through a package manager for it to work. For example, in a Debian or Ubuntu system, we would use:

debian

    apt install expect

fedora

    sudo dnf install snapd

Let’s save this script into a file named expect-script.exp, and run it:

    chmod +x answers.exp
    ./answers.exp


    autoexpect questions.sh