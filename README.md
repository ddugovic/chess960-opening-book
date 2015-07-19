chess960-opening-book
=====================

Chess960 opening book in PGN format, depth 3, with 128137 unique positions including castling rights.

Can be compiled into PolyGlot opening book format, for example:

    polyglot make-book -pgn chess960_book_3moves.pgn -bin chess960_3moves.bin -min-game 1 -uniform
