Overview
========

This document describes the XRootD implementation of the GSI protocol [rfc3280,rfc3820]_; the XRootD protocol is described in [xrdProto]_.
The protocol version described in the document corresponds at the head of the GIT master branch at the time of writing,
which is supposed to go in v4.9 (internal version of the GSI protocol 10400). This includes the verification of the server identity,
as explained in the related section.
Notable changes with respect versions prior to v4.9 (internal version lesser or equal to 10300) are described in Appendix C.

Related documents
^^^^^^^^^^^^^^^^^

The cryptographic functions used by the GSI protocol implementation are provided by XrdCrypto [xrdCrypto]_.
A set of utilities used in common with the PWD authentication modules is provided by XrdSut [xrdSut]_.

