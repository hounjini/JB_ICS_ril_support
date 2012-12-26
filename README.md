This repo contains jellybean-4.1.2- frameworks mod for supporting ICS ril.

RIL.java proceed new libril features that is not supported by old libril (libril.so version 6)

RIL.java implements new ril features by itself.

RILConstants.java includes necessary variables for supporting old libril.so

If you are not using HTC libril, please set HTC_ICS_RIL variable false in the RIL.java. (Default is true)
