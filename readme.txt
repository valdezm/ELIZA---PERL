Mark Valdez
March 1, 2008
Perl 1

I couldn't really think of additional functionality that would display my aptitude of Perl. I just keept coming up with trivial(in implementation) responses to triggers, such as: (user)"This is stupid", (eliza)"Stupid is a stupid word". I think some thing cool would be the allowing a programmable mode where the user can input tags and responses to the tags, the program can then store those results in some file. That would be nice. I currently implemented the extra-credit problem. I also implemented a simple response to Hi or Hello, although I didn't use the Case Insensitive op, I may have hard-coded the limited options. I really enjoyed this assignment, Perl has much functionality that makes the program implementation easier. I couldn't figure out how to send a list as a value for some hash pair. So I just wraped the list in quotes and sent the string. Then splited the string to a list.

These are some of the test cases that I used frequently to test behavior of Perl.

## ITERATIVE TEST CASE:
##
## print "@key_nouns"; #test-disp for nouns correctness
## print "@key_emotions"; #test-disp for  emotions correctness
## print "@words \n $last_char"; #test-disp for last char and reconstruct original last word    
## for (my $i = 0; $i < @words; $i++) #iteration
## {print "$words[$i] |";} #iteration
## print $words[$#words] . @words; #test-disp for end


