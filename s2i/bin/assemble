#!/bin/bash
 echo "---> I am in assemble script ..."
# restore build artifacts
if [ "$(ls /tmp/artifacts/ 2>/dev/null)" ]; then
    mv /tmp/artifacts/* $HOME/.
fi

# move the application source
mv /tmp/s2i/src $HOME/src

