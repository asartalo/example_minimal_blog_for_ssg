+++
title = "Exceptions are Part of the Interface"
date = "2024-02-26T15:20:00+08:00"
draft = false
slug = "exceptions_are_part_of_the_interface"

[taxonomies]
tags = ["dev notes"]
+++

I think I've known this for a long time now but it's only today that I've fully articulated this by myself. A lot of smarter people have talked about this before but it's only today that I've put this idea into words on my own.

The reason why I appreciate Go's "errors as values" approach and the enums in Rust is that in those languages, I tend to write functions/methods that are more explicit in their behavior. I tend to declare this behavior in the interface itself.

Exception handling as a strategy adds some cognitive tax to my code. Those exceptions are part of the interface even when they are not explicitly declared.

