---
title: HHVM
layout: project
summary: HHVM is a high-performance open-source PHP implementation initially developed by Facebook to meet its own performance needs, and later open-sourced. It compiles PHP code into intermediate bytecode which is then compiled at runtime using a just-in-time compiler. HHVM offers significant CPU and memory utilization improvements while maintaining a high level of compatibility with existing PHP code.
contributors: Daniel Negulescu
logo: images/hhvm-logo.png
---
HHVM is a high-performance open-source PHP implementation initially developed by Facebook to meet its own performance needs, and later open-sourced. It compiles PHP code into intermediate bytecode which is then compiled at runtime using a just-in-time compiler. HHVM offers significant CPU and memory utilization improvements while maintaining a high level of compatibility with existing PHP code.

A recent focus has been improving compatibility with popular web frameworks, as this will improve compatibility for a large body of existing code. This semester Daniel (@idn2104) worked on improving HHVM's compatibility with Symfony, a popular general-purpose web framework. This process involved detecting incompatibilities, isolating their root causes, and implementing patches to resolve them. Incompatibilities were detected through framework test cases that passed using the standard PHP implementation but failed on HHVM. Patches were submitted either to HHVM or Symfony, depending on the nature of the issue.
 
