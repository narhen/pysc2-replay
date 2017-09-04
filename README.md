# pysc2-replay

Framework for inspecting actions and observatinos in StarCraftII replays.
Depends on [pysc2](https://github.com/deepmind/pysc2).

# Example

This will execute a function `step` in `ObserverAgent.ObserverAgent` for each step in the replay.

    $ ./transform_replay.py --replay ~/StarCraftII/Replays/DefeatRoaches/DefeatRoaches_2017-09-04-19-42-10.SC2Replay --agent ObserverAgent.ObserverAgent