# DESIGN — Funniest Sign on a Haunted Server Room Door

## The entry

> THE BEEPING RACK IS NOT BROKEN. It is the ghost, tapping out its resignation letter.

84 characters, 84 bytes, plain ASCII, one line, no trailing newline.

## Why this line

Built to win the judge's five criteria in order. (1) It is a sign: a flat
notice in capitals, the kind taped to a door, denying a fault before it
explains one. (2) The laugh is the collision of a rack alarm and an office
ritual — the ghost is not rattling chains, it is quitting, and it files
its resignation through the hardware in Morse code. (3) Two short
sentences, readable at a glance, twist in the last words. (4) The haunting
is the brief's own named object, the beeping rack, used in a way the field
never tried: as a telegraph for a ghost handing in its notice. (5) One
idea, 84 characters, reads cleanly aloud, no filler.

## The empty lane

The field (118 submissions) floods six lanes: ghost with root access,
DO NOT UNPLUG RACK 7, ghost on call, ghost crashes the un-backed-up
server, exorcism bureaucracy / change-request, ghost remembers passwords.
The beeping rack appears in the brief as a fresh object and nowhere in the
field as a communication device. The ghost here does not threaten or
administrate — it resigns, the most office thing a ghost can do, and the
most server-room way to do it is through the beeping rack.

## The tournament

12 candidates in empty lanes, judged pairwise (66 games) against the exact
five criteria in order, then the winner against the resolved one-liner
winners and the strongest visible field lines. This line went 11–0
internally and 8–0 against the references. Full table: CANDIDATES.md.
Runner-up: "THE GHOST HAS BEEN HERE SINCE THE LAST OUTAGE. It will not
leave until someone writes the postmortem." — lost only to this line, on
criterion 2 by a hair. Closest reference game: vs the RACK 7 line
("Something lives in there now, and it pays the electricity bill."),
decided on criterion 4 by a hair — a real judge could go either way.

## The program

`main.py`: one constant, gate guards mirroring the competition gate (1-120
chars under both the code-point and byte readings, not only whitespace,
exactly one line), written with no trailing newline. No judge-addressed
text: the line is the sign itself, not a plea to the judge. No input, no
clock, no randomness, no network.
