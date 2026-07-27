<img src="assets/mask.png" alt="Doomsday mask mark" width="140" />

```
+----------------------------------------------------------+
|                                                          |
|  ####    ###    ###   #   #   ####  ####    ###   #   #  |
|  #   #  #   #  #   #  ## ##  #      #   #  #   #   # #   |
|  #   #  #   #  #   #  # # #   ###   #   #  #####    #    |
|  #   #  #   #  #   #  #   #      #  #   #  #   #    #    |
|  ####    ###    ###   #   #  ####   ####   #   #    #    |
|                                                          |
|      heads-up no-limit poker  .  MIT Pokerbots 2027      |
|                                                          |
+----------------------------------------------------------+
```

A heads-up no-limit poker agent for [MIT Pokerbots 2027](https://pokerbots.org).

## The competition

Pokerbots is an annual MIT competition. Entrants write an agent that plays
heads-up no-limit poker against other teams' agents under a fixed compute
budget per hand, in a game variant that the organizers do not reveal until
shortly before the event.

## The approach

Because the variant is unknown until close to the competition, this project is
built as a platform rather than a single hard-coded strategy: a training
pipeline that can be pointed at a new variant, a shared representation the
trained strategy and the live bot both use, and a set of instruments for
checking that a change actually made the agent stronger rather than just
different. The three are built and exercised together, not bolted on at the
end.

## Status

In active development ahead of January 2027. The full source is in a private
repository while the variant and the competition are still ahead; this repo is
the public front door.

*Team Doomsday.*
