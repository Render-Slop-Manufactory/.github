# Render Slop Manufactory

I have AI tokens to burn.

This org is basically an experiment to see how far I can get building rendering-related Rust stuff through AI orchestration without personally understanding every deep implementation detail beforehand.

The process is roughly:

```text
have questionable idea
        ↓
make AI research it
        ↓
make AI implement it
        ↓
make another AI review it
        ↓
write tests because nobody should trust any of this
        ↓
repeat
```

I'm still making the architectural decisions, choosing what to investigate, reviewing results, and trying to stop the agents from confidently inventing nonsense.

Maybe some of the resulting code will actually be useful.

## Current slop

- [fsr-sdk-rs](https://github.com/Render-Slop-Manufactory/fsr-sdk-rs)
- [bevy-render-enhancements](https://github.com/Render-Slop-Manufactory/bevy-render-enhancements) (not actually published yet)

## What is the point?

Mostly curiosity.

I want to see how far AI-assisted software development can be pushed when the human is orchestrating, reviewing, testing, and making decisions without necessarily being the domain expert who could have written the whole thing from scratch.

That means there will probably be:

- excessive research for tiny implementation details;
- agents arguing with other agents;
- code spikes for absurdly specific questions;
- suspicious amounts of documentation;
- APIs getting redesigned when reality disagrees with the original plan;
- actual useful code hiding somewhere in the pile.

Everything here should be considered experimental unless a project explicitly says otherwise.

If you find something useful, nice.

If not, at least the tokens died doing what they loved.
