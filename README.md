# dojo

<p align="left">
  <img src="./assets/1.JPG" height=300 />
  <img src="./assets/2.PNG" height=300 />
</p>

a repo for learning stuff by DIY. become less dumb.

pick something you don't really understand, an emulator, a ray tracer, a shell, a VM,
whatever and figure it out by making one.

AI is allowed. i mean you can't really escape it anymore. It just doesn't get to do the project for you.

It's a tool to explain concepts, answer questions, review what you wrote, help debug,
point you at good docs, and give hints.

understanding and implementation are yours.

## why

i've been using AI a lot recently.

it's useful, obviously.and it is getting better day by day. But it’s also very
easy to go from “this saves me time” to “wait, could I still build this myself?”

when I'm trying to learn something new, getting the
answer too quickly kind of ruins the interesting part.

I don't just want to know _what code makes an emulator work_. I want to understand
what the CPU is doing, why the emulator is structured that way, get a few things wrong,
and eventually make it work myself.

So that's what this repo is for.

Pick something you want to understand. Read about it. Build a bad version.
Discover that your mental model was wrong. Fix it. Repeat.

Code is just how you make the idea concrete.

## how it works

1. Clone the repo.
2. Open it with your coding agent.
3. Tell it what you're curious about.
4. Pick a project.
5. Start figuring it out.

When you ask for help, the agent starts small: questions, hints, things to read, explanations.

If you're really stuck, it can get more concrete, up to pseudocode.

It just won't write the implementation for you.

`NOTES.md` is there for dumping what you learned, what confused you, what you tried, and whatever finally made something click.

## one rule

no AI-written project code.

Not because typing code by hand is sacred.

Because having the answer dropped into the repo defies the point

There are some ideas in `PROJECTS.md`:

- emulator
- ray tracer
- shell
- malloc
- bytecode VM
- CUDA stuff
- anything else you want to understand badly enough to build

The list is just there for ideas. Bring your own rabbit hole.

## ...

**Why would I do this to myself?**

to become less dumber.

**Can the agent explain something I know nothing about?**

Yep. That's kind of the point.

Ask dumb questions. Ask it to explain something three different ways. Ask for papers, docs, diagrams, examples, whatever helps.

**Can it help with compiler errors / build problems / toolchain nonsense?**

Yep.

It can help you understand what's going wrong. You make the actual change.

**What if I'm completely stuck?**

Keep asking.

The hints can get progressively more specific, all the way to pseudocode.

You still have to connect the dots and make it work.

**Why projects?**

Because "I think I understand this" and "I built one" are very different feelings.
