<!--- @file
  Security Advisory of issue "Dns pack size check"

  Copyright (c) 2019, Intel Corporation. All rights reserved.<BR>

  Redistribution and use in source (original document form) and 'compiled'
  forms (converted to PDF, epub, HTML and other formats) with or without
  modification, are permitted provided that the following conditions are met:

  1) Redistributions of source code (original document form) must retain the
     above copyright notice, this list of conditions and the following
     disclaimer as the first lines of this file unmodified.

  2) Redistributions in compiled form (transformed to other DTDs, converted to
     PDF, epub, HTML and other formats) must reproduce the above copyright
     notice, this list of conditions and the following disclaimer in the
     documentation and/or other materials provided with the distribution.

  THIS DOCUMENTATION IS PROVIDED BY TIANOCORE PROJECT "AS IS" AND ANY EXPRESS OR
  IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF
  MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO
  EVENT SHALL TIANOCORE PROJECT  BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL,
  SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO,
  PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS;
  OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY,
  WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR
  OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS DOCUMENTATION, EVEN IF
  ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.

-->

# 32. DNS Packet Size Check {#dns-pack-size-check}

## Description:

Buffer overflow in network stack for EDK II may allow unprivileged user to potentially enable escalation of privilege and/or denial of service via network. 

## Impact:

Escalation of Privilege and/or Denial of Service 

## Severity:
7.2 (High) - CVSS:3.0/AV:N/AC:L/PR:N/UI:N/S:C/C:N/I:L/A:L

## Recommendation:

EDK II Commit:

- https://github.com/tianocore/edk2/commit/84110bbe4bb3a346514b9bb12eadb7586bca7dfd

Patch:

- https://bugzilla.tianocore.org/attachment.cgi?id=124

## Acknowledgments:

Intel Team

## References:
CVE-2018-12178

EDK II Bugzilla  [#809](https://bugzilla.tianocore.org/show_bug.cgi?id=809)
