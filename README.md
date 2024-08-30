# Saturnium, AKA Rumplemints, Ample Sternum, Strong Panda

Saturnium is a keyboard layout designed for:

- Lowest possible redirects (3 keys in a row on one hand changing direction),
  featuring `STR` and `MPL` rolls
- One-handedness (like a stringed instrument with a stationary right hand, and
  kinda like dvorak)
- Spatially mnemonic for code editor commands (`BF`/`PN`)
- SFBs in the strongest fingers/directions (with high LH lateral movement and
  active left-pinky)
- Tolerance for/desire to alt-finger-overlap middle and index

It works best with a traditional staggered keyboard to make the intentional
alt-fingerings most comfortable. And since the right hand is so few keys, it
doesn't much matter that RHS has a weird angle.

```
    q
  b f l p x    y o u
  s t r n m    h e i a
v g k c d w
```

Rough stats from Oxey's Playground (slightly fudged by removing puncs and
approximating for keys outside the grid):

```
Sfb:  2.8%
Dsfb: 7.1%
Lsb:  0.3%

Inrolls:     12%
Outrolls:    26%
Total Rolls: 37.6%

Onehands:          1.538%
Total Alternates: 42%

Redirects:       0.95%
BadRedirects:    0.26%
Total Redirects: 1.21%

finger 0: 10.91%     finger 9: 7.92%
finger 1: 11.80%     finger 8: 9.94%
finger 2: 13.18%     finger 7: 19.29%
finger 3: 16.92%     finger 6: 6.53%
```

Things to note:

- The `CD` key-combo makes `J`, and `GK` makes `Z`.

- That leaves an extra slot above `H` in case you wish to bring `W` or `M` or
  `S` over there.

- `STR` and `MPL` are nice tight rolls. They show up roughly 140 and 50 times
  respectively in an English-top-10k-words list (EN10k).

## Low redirects how-to

If you hadn't noticed, several modern popular keyboard layouts feature
anti-redirect patterns like `str`. Consider [sturdy] (`strdy`), and any
NERPS-based (`nrts`) layout (see the `str` backwards?). Saturnium is no
different, but takes it even further. Many redirects are a a result of the
vowel hand having a high-freq consonant, like `N`.

I'd even consider the presence of an `STR` roll a key defining factor in a
layout. All of these embraced it: G/G, Sturdy, dsthk-v1, Engram, ctgap, nerps.
And several layouts have avoided it altogether by putting `T` or `R` on thumb.

Of the 3-consonant runs, here is what works (rolls) and doesn't with Saturnium:

GOOD: **str rts mpl mpt mpr xpl xpt nts rks nks nct cts rtg stm src**

BAD: **rst ntr nst spr ckl ngl ntl**

## Programming editor friendly

With the assumption that `Ctrl` (`^`) is left of pinky, several shortcut keys
need to be placed in easy reach. Here are the possibilities (`x`s):

```
  x x x x
^ x x x x x
      x x
```

The most important ones (for Emacs/CLI and others) are `BFPN` for _Back,
Forward, Previous, Next_. In an ideal world, those make the home row, to become
something like: `^ B F P N`

What ended up in Saturnium is about as good as you can do with this in mind.
Other important ones to keep on strong-hand: `CDLXGKW`, though they aren't
used in succession so can be in harder spots.

This design factor was the number reason I didn't just go with
Gallium/Graphite or Sturdy: having `BN` together on pinky (G/G), or `FNB` on
the wrong hand (Sturdy) couldn't work.

## SFBs explained

The worst SFB statistically by far is `ND`. It doubles the stat. However, it
exists intentionally since it's a very comfortable and strong downward alt
using middle-finger for `N`. You may want to do magic for `A -> AND`
anyway, which covers a lot of other words, like `cANDy`.

## Programming language friendly

Given the low redirects, vowel-less words are easier to type.

There was also consideranion given to making a small set of keywords
comfortable to type. Though not totally designed for, consider these
buttery-smooth examples:
select, table, from, where, defn, mapv, sql, src, function

## Vowels on the left too

You can use key combos for `A` (I use `BF`) and others to get any missing key
combos (`Ctrl-A` etc).

## Going fully one-handded

Despite some obvious downsides, the **benefits of a one-handed** layout (left
hand in this case) are many:

- Weak Hand (WH) can use the mouse while Strong Hand (SH) uses the shortcuts
- An injured WH can do 1- or 2-finger pecking
- The more dexterous SH can learn intricate patterns while WH remains simple

To take it further:

- `N` can become an adaptive `NH` (so `H` somewhat disappears)
- `Y` can replace `X` (which becomes a combo)
- `A` goes to left-Ctrl
- `E` goes to left-thumb (no more magic)

That leaves `OIU` for the foot pedals or what-have-you.

## About those high SFBs

If the high SFB number bugs you, you can swap `C` and `D` to drop almost in
half. But that just gets rid of `ND`, which is a great middle-to-index alt.
Most of the rest of the SFBs are from the `LRC` column.

## Is this proven to work?

I'm the only one using this so it's hard to know if it will work for you. If
you're already comfortable with Sturdy, it's got a lot in common with it; the
key difference being `N` on the other side. The rest of Sturdy's RH would be
fine to stick with.

## Available tweaks

Here are some alternative positions I found to also work pretty well:

- Put `Y` on the bottom row far from `OU` (I do this) becuase putting it on
  the top next to them is a worse position, and `Y`-_magic_ does `you`
- Swap `M` and `D` if you want an easier `LD` reach
- Bring-your-own vowel cluster
- Swap `Y` and `X`
- Move `M` or `W` to upper-right index (more redirects though)
- `G` or `W` can go on left-shift
- `F` can go to qwerty-`G`, and `M` to qwerty-`B`

## Letter specific details

- `W` is a reach but is so often paired with a RH key
- `V` is infrequent enough; I like left-shift position better than qwerty-`T`
- `X` is a least favorite reach, but pairs/rolls well next to `P`

## Backstory

If I could do it all over again, I may have saved myself months of design
struggle and just gone with Nerps (with a couple tweaks: `LFBK`). But it would've
been harder for me to learn, from where I was.

This started as an effort to get `N` over to LH becuase I wanted `BFPN` all
together. And also, redirects were feeling like the clumsiest thing I'd been
facing.
