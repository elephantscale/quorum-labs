# Quorum 

Based on Ethereum, Quorum is an open source blockchain platform that combines the innovation of the public Ethereum community with enhancements to support enterprise needs. Our mission is to make adopting blockchain a seamless process.

# Environment
We will use docker ubuntu for this course.

`docker run -it -p 9615:9615 -p 22000:22000 -p 22001:22001 -p 22002:22002 -p 22003:22003 --name=quorum  fenago/ubuntu`

# Quorum Setup

This repository contains setup for Quorum.

Current example is:
* [5nodesRTGS](https://github.com/bacen/quorum-examples/tree/master/examples/5nodesRTGS): Starts up a set of 5 nodes that simulates a Real-time Gross Setlement environment with 3 banks, one regulator (typically a central bank) and an observer that cannot access the private data. 

The easiest way to get started with running the examples is to use a clean Ubuntu 16.04 environment (see README at 5nodesRTGS directory).

**Important note**: Any account/encryption keys contained in this repository are for
demonstration and testing purposes only. Before running a real environment, you should
generate new ones using Geth's `account` tool and `constellation-enclave-keygen`.

## Usage
```sh

mkdir lab && cd lab
git clone https://github.com/athertahir/quorum-examples.git
cd quorum-examples
cd examples
cd 5nodesRTGS
chmod 777 *.sh
./bootstrap.sh
# (run as root, should take some user confirmations, requires internet connection)
```

**Note:** You will be prompted to press `ENTER` multiple times during bootstrap.

## Verify

You will get following output at the end.

```
 #####
#     #  #    #   ####   #####   #    #  #    #
#     #  #    #  #    #  #    #  #    #  ##  ##
#     #  #    #  #    #  #    #  #    #  # ## #
#   # #  #    #  #    #  #####   #    #  #    #
#    #   #    #  #    #  #   #   #    #  #    #
 #### #   ####    ####   #    #   ####   #    #

Quorum has been installed.
```

Verify that the setup was successful by running: `geth --help`

In the next step, we will run 5nodesRTGS Quorum Examples `5nodesRTGS`. Please use the same container for the next lab as well.