# filter-ascii.c
 Create "filter-ascii.c" to check if a bytestream contains non-ASCII data. ASCII is a 7-bit encoding, so any byte > 127 is non-ASCII. The program reads from stdin and checks each byte. If all bytes are ASCII, it prints "ASCII data." If a non-ASCII byte is found, it reports the byte's value and position, plus any following non-ASCII bytes. coded C
