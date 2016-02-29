## Chapter 5: Format and Control

To encounter the universal Turing machine underpinning the electronic book *as
a mechanism*, the media and book historian will find that it borrows from a
number of extant designs, which, together and incrementally, give the
universal Turing machine its physical form. Once we have grasped the notion of
the Turing machine as a piece of software, an algorithm, I am compelled to
wonder about its history as a mechanism and ask, what are its technological
antecedents? What would happen if Turing attempted to patent his device, for
example? What previous art and related designs would he have to cite in his
application? In an answer to these question we discover, perhaps
unsurprisingly, that the Turing machine belongs to a long lineage of
controlling devices. This entails also that the book, subsumed by computation,
also embodies a part of the same material history.

Most of the minimal physical requirements to build a universal Turing machine
were within reach in the 1930s, at the time Turing authored his influential
paper. In practice, his proposal would require first, an apparatus capable of
"scanning" and "erasing" a "finite number of symbols." Second, we would need
what Turing calls "one-dimensional paper," divided into discrete squares "like
a child's arithmetic book" [@turing_computable_1937, 249].[^ln1-infinite]
Furthermore, we would need some sort of a mechanism to advance tape through
the machine, or, alternatively, to propel the scanning mechanism along the
length of the tape. Having assembled these elements, our creation would look
roughly like a cross between a telegraph, a film projector, and a
typewriter.[^ln1-davey]

Were we to patent the Turing machine in the United States, at the time of its
invention, the above elements would find prior art in mechanisms such as the
"Numeral adding or subtracting attachment for type-writing machines"
[@daugherty_numeral_1894], "Combined Type-writing and Computing Machine"
[@degener_combined_1911], "Computing Attachment for Typewriters"
[@wright_computing_1914], "Computing Mechanism" [@wright_computing_1915], and
"Combined Type-writing and Adding Machine" [@ellis_combined_1914] among
others. All of these machines contain some combination of a reading and
writing "head," storage tape, and movement mechanism as specified in Turing's
paper. A number of inventions at the end of the nineteenth century pertain
specifically to "circuit-controlling devices controlled by a traveling
perforated strip or tape" [@cuttriss_telegraphy_1893]. Prior to perforated
tape, the transmission of messages by telegraph required the presence of a
skilled operator, able to transcribe messages from text to Morse code, and
into the physical motion of a lever-operated circuit. In the operation of
early telegraphy, the human operator acted as a mute interpreter between text
and telegraph. The transcription of text into signal, and back onto paper,
required the real-time presence of human encoders and decoders.
The perforated tape decoupled the human from the machine. In US1187035 (1916)
on "Telegraphy", Albert and Ralph Bumstead explain: "the object of our
invention is to provide a system of telegraphy which does not require skilled
operators for the transmission and reception of messages"
[@bumstead_telegraphy_1916]. Instead, the message was transcribed into
perforation via mechanical means and then fed into the mechanism. The tape
mechanics of the typewriter could then be coupled with the electrics of the
telegraph, with perforated tape acting as a mediator between the two "worlds"
of mechanics and electricity. A number of contraptions emerged at the time
with the aim of transfiguring the mechanical action of the typewriter into
perforation, and, consequently, perforation into script, completing the
circuit between automated "encoding" and "decoding." As one machine converted
human input into mechanical states, and into signal, another machine converted
signals into mechanical states and thereon into human-legible messages.

A multitude of inventions capitalized on the control capabilities of removable
storage media by the beginning of the of the twentieth century. These included
machines for tape-controlled telegraphic transmission
[@wheatstone_improvement_1874; @murray_tape-controlled_1905;
@bumstead_telegraphy_1916], tape-controlled printing [@creed_printing_1911],
printing telegraphs [@hallden_printing-telegraph_1929], and remote broadcast
programming devices for radio and television content [@vriendt_program_1934;
@brown_automatic_1936; @brown_selective_1936]. With the invention of punch
cards and perforated tape (also used in textile looms, as early as 1725), a
message meant for another human became also a physical medium---bumps and
holes---used to animate the mechanical movement of the transmission apparatus.

For example, of the 33 asserted claims in the Bumstead brothers' "Telegraphy"
patent, the first 13 relate to the "transmission of intelligence,"

> [...] adapted to initiate a succession of electrical impulses all of which
> have a character representing significance, a receiver adapted to detect
> variations in time intervals elapsing between successive impulses, a
> plurality of interpreting relays selectively actuated by said receiver, and a
> printed mechanism responsive for the combined action
> [@bumstead_telegraphy_1916, 12-13].

What begins as a description of a mechanism for information transmittal, ends
with a claim about hermeneutics of control. Starting with clause 14, the
brothers begin to describe "a telegraph system" capable of "transmitting
impulses" at varying time intervals. In the language of the patent, the length
of the time interval "represents significance," involving an automated
receiver responsible for "distributing, interpreting, and recording." The
printing mechanism is further "arranged to print the interpretation of the
signals which is made by the interpreting relays" [@bumstead_telegraphy_1916,
6]. The interpreting relays transform time intervals into a "typographical
form" representing "a letter, a figure, or other characters," "in accordance
with a code" [@bumstead_telegraphy_1916, 13]. Initially, the telegraph prints
to "transmit intelligence." But the authors also understand that the varying
time intervals could also signify other information, meant to actuate a
variety of devices. By the middle of the patent, the brothers describe their
telegraph as a general "controlling medium," which can power everything from
typesetting machines to more general "sunflower switches." "Indeed the
detector and the interpreting relay could be made to actuate a set of
sunflower switches for an indicator without including a printer at all," the
authors conclude [@bumstead_telegraphy_1916, 12].

Along with hundreds of similar inventions patented around the turn of the
twentieth century, Bumstead brothers describe a mechanism that could function
as a Turing machine with little modification. The automated telegraph, driven
by ticker tape, and connected to a printer contain all the necessary
requirements set out by Turing: a discrete symbolic language, the removable
storage medium, and a device that can alter its internal states based on the
reading and writing of scanned symbols. They are able "read" and "write" and
otherwise manipulate symbolic representation, they ingest tape, and they
covert symbol into internal structure. By 1905, Donald Murray, the inventor of
the popular Murray telegraph, could write that "if we disregard the small
class of telegrams that merely express emotions, *the essence of telegraphy is
control* [emphasis mine]." He wrote also that "telegraph systems, therefore,
belong not to the class of producing or distributing, but to the class of
controlling mechanisms" [@murray_setting_1905, 556]. For the automated
telegraph, control code and the message are one. The mechanism interprets some
signals as figure and character and other signals as control code affecting
the internal mechanical configuration of the device. The first type of code
holds "significance" for humans, where the second for the mechanism itself. It
is "transmitting intelligence" in a sense of externalizing machine states and
"interpreting" in the sense of mechanical reconfiguration of internal parts.

By 1936, when Turing published his paper on computable numbers, these
inventions do not merely anticipate the modern computer, they were brought to
mass market in the widespread manufacture of computing scales, dial recorders,
electric tabulating machines, and computing typewriters made by companies like
Underwood Computing Machine, Electromatic, and International Business Machines
(IBM). Rather than a single eureka moment, the invention of the universal
machine should therefore be viewed as a gradual historical process that
culminates in Turing's universal (and minimally viable) specifications. What
does the material history of the computer mean for the history of the book?
The electronic book is, after all, a kind of a computer. It is a Turing
machine. It belongs therefore in part to a class of controlling devices, as
described by Murray and Baumstead. To discover the book in the guise of a
*computational* literary artifact means coming to terms with it as a kind of a
robot---a device for remote machine control.

Furthermore, the very metaphysical nature of Turing machines implies the
irreversible admixture of matter, content, and control structure. When reading
a paper and cloth book, one can definitively isolate a) the physical
properties of paper and cloth from b) the content of the book and from c) the
legal and political elements governing the production of textuality. To wit:
tear out the copyright notice along with the ISBN number, copy the words into
a notebook, and recycle the paper. The literary device, by contrast, ingests
both symbolic representation and control code through the same input stream.
Where images of governance (like trademark and copyright symbols) *signify*,
computed text *embodies*. Computation enacts control in exactly the sense by
which Wittgenstein suggests to insert a layer of "rules for obedience" between
symbol and interpretation.

In the process of textual production, printing and typesetting, it is certain
that my words were mixed with machine language, which in turn changed the
structure of the devices in your lap, in your hand, near to your eye,
embedded, or embodied. I could say that I bear no responsibility for extending
the reach of machine language so close to the reader. But that would be
factually incorrect. The choice of my writing implements and my channels of
communication affect deeply the contexts of interpretation. Such choices, in
aggregate, define the shared ecosystem of knowledge production. Traditional
strategies of close reading which limit interpretation to the parsing of
visible content risk missing the concealed machinations of naked circuit
control. It looks like you are reading a book, but this book may change
depending on the readers race, gender, ethnicity, geography, or political
affiliation. Who has agency to program the device? Were a book also a pill or
fused with the neural circuitry of the brain, would you know what and whom you
were reading?

I began the book by asking the reader to answer a seemingly innocuous
question: Where does the computed sign reside? The outlines of an answer led
us to multiple sites of inscription, some visible and some hidden, some
legible and others opaque. I have suggested also that the familiar distinction
between form and content fails to capture the crucial "formatting and control"
layer of the computed sign. In the following sections I would like to explore
the curious contradiction at the heart of formalism itself. Historically, form
has been used to signify both the material shape of the sign and the idealized
archetypal "rule book" for its creation. The two senses matter because they
lead to opposing strategies of interpretation. One seeks to describe, the
other to explain; one to perceive, the other to reveal.

My task in this chapter is to bring the formatting layer into view. The
distinction between form, format, and formula will give us the vocabulary to
discuss the codification of document structure in the second part of the
chapter. As I will argue, some of the same intuitions that guided the
intellectual history of formalism became also ingrained in the material
contingencies of word processing emerging in the middle of the twentieth
century. The history of something called the Document Object Model will give
us the means to reveal a layer of formatting shaping every digital document.

Formatting structures facilitate the conversion of machine-readable codes into
human-readable text. Yet formatting continues to elude the critical gaze
because the very concept of form, central to literary analysis, contains in it
two conflicting ideas. Going back to reception of Plato, Hegel, and the
Russian formalists, the English "form" renders at times the material, outward,
and apparent shape of something said or pictured. Yet just as often, critics
use "form" in the sense of a Platonic ideal: abstracted from matter,
inward-facing, and in need of explication. Form in that sense is closer to the
idea of an algorithm of a formula.

### 4.1 Form and Formula

The intellectual history of formalist thought in literary theory contains
within it two distinct and contradictory ideas about form: one about the
outward shape of the sign and another about the inward structure or formula
that governs semiotics. The distinction is important because it leads to
several conflicting strategies of interpretation. Taken in the sense of
"outwards shape," form suggests an aesthetics or even an "erotics" of art
[@sontag_against_1966]. On this view, a sign is forever embedded into the
specific contexts of its instantiation. The physical peculiarity of this word
makes it forever different from the same word on a different page. Taken as
formula, form suggests a more analytical approach, aimed at explicating hidden
structures. Formal analysis in that sense studies not specific traces or
utterances, but the development of ideal forms, which exist independent of any
specifics.  The distinction between "form" and "content" is one of the basic
binaries in any formalism, mobilized often in literary criticism and computer
science alike. "Classical art, in a word, stands for form," R.G.  Collingwood
wrote in 1929, and "romantic art for content" [@collingwood_form_1929, 335].
In a much more recent work on computational text generation, Kathleen McKeown
writes that to produce discourse, writers and speakers "must decide what to
say and how to present it effectively." A machine that generates text should,
among other things, be able to determine the "content and textual shape" of
what needs to be said or written [@mckeown_text_1992, 1]. Similarly, in her
influential essay "Print Is Flat, Code Is Deep," Katherine Hayles writes about
"the interplay between a text's physical characteristics and its signifying
strategies" [@hayles_print_2004, 72].

Like many foundational dichotomies in the Western tradition, the distinction
between form and content has its roots in Platonic thought. For Plato, the
"essence" or an "idea" of something (like a chair) exists in an ideal,
metaphysical state, somewhere beyond the confines of the material universe. By
contrast, a physical instantiation of that object (a specific chair) embodies a
somewhat more limited, even corrupted, version of that perfect idea. The task
of the philosopher becomes one of reconstructing the single ideal notion of the
perfect chair from its many imperfect instantiations. A computer scientist will
recognize in this chain of reasoning some of the principles behind
object-oriented programming: a way of building software that works by defining
abstract "object classes" and invoking them as "class instances"
[@hoare_record_1965; @nygaard_history_1981]. Similarly, for Plato and later for
René Descartes, G.W.F. Hegel, and other so-called "idealists," ideas provide us
with lasting universal "templates" for instantiation within the contingent and
always changing physical confines of the material world.[^ln4-descartes]

In Plato we find a number of words that, depending on the translation, stand in
for the English "form." These include *eidos* (essence), *idea* (idea),
*morphe* (shape), and *phainomena* (appearance). Compare, for example, several
translations from Plato's *Timaeus*. The text shows Timaeus, the titular
character, explaining the nature of the physical world to his collocutor. In a
passage that anticipates the famous "molten wax" analogy in Descartes, Timaeus
notices that some elements, like water, change their appearance
(*phantazomenōn*) while remaining essentially the same substance. Benjamin
Jowett translates the passage:

> Thus, then, as the several elements never present themselves in the same form
> [*phantazomenōn*], how can anyone have the assurance to assert positively
> that any of them, whatever it may be, is one thing rather than another?
> [@plato_timaeus_1998, 49d]

In another translation, W.R.M. Lamb translates the Greek *phantazomenōn* as
"appearance":

> Accordingly, since no one of these ever remains identical in
> appearance,[*phantazomenōn*] which of them shall a man definitely affirm to
> be any one particular element and no other without incurring ridicule?
> [@plato_plato_1955, 48d]

Both translations capture the plain meaning of the passage: the essence of a
thing remains even as its outward appearance changes, taking on a phantasmal,
fantastic, ghostly, imaginable, and even "virtual" shape and appearance (all
reasonable English approximations of the Greek *phantazomenōn*). Accordingly,
Jowett translates *phantazomenōn* (that which is changeable) as "form" and Lamb
as "appearance."

Contrast the *Timaeus* passages with the ones in *Cratylus*, about name-giving.
In *Cratylus*, Socrates and Hermogenes discuss the ways in which words signify
things by convention. "What has the carpenter in view when he makes a shuttle?"
asks Socrates. "Is it not something the nature of which is to weave?"
Hermogenes agrees. "Well, then, if the shuttle breaks while he is making it,
will he make another with his mind fixed on that which is broken, or on that
form (*eidos*) with reference to which he was making the one which he broke?"
Hermogenes agrees the carpenter would fix his mind on the ideal form. In that
case, we should properly call *that* the real shuttle (*estin kerkis*),
Socrates concludes---his point being that the exact outward appearance of
individual shuttles does not matter as much as the abstracted idea of shuttles.

The abstraction endures as given instantiations break and shatter. There exist
different types of shuttles, some used to weave wool and some for linen, but
all of them, in Jowett's translation, "must contain the form or ideal (*eidos*)
of shuttle" [@plato_dialogues_1937, 389a-b]. In *Cratylus*, *eidos* stands for
the "universal lasting ideal" of all shuttles: exactly the opposite of
*phantazomenōn* as "ephemeral instantiation" in the previous passage! Yet both
*eidos* and *phantazomenōn* were reasonably translated into English as "form,"
indicating a fundamental overloading of the concept.[^ln4-plato]

G.W.F. Hegel gives perhaps the paradigmatic expression to the dichotomy
between form and content in the literature on aesthetics. In his *Lectures on
Aesthetics*, Hegel posits classical art as striving to reach an equilibrium
between its ideational, spiritual content and "the configuration of sensuous
material" [@hegel_hegels_1998, 70]. Whole books have been written on Hegel's
rather technical and sometimes idiosyncratic vocabulary. Rather than define
terms precisely, Hegel likes to bombard his reader with semantic cognates. On
the side of "content" (*Inhalt*, *Gehalt*), he evokes words like inner life
(*Innere Lebendigkeit*), feeling (*Empfindung*), soul (*Seele*), and spirit
(*Geist*). All of these convey a movement inward to a location (if it can be
called such) beyond the physical world, accessible only to the spirit
(*Geist*) or mind (*Gedanken*, *Verstand*). On the side of "form" (same in
German), Hegel accumulates words like expression (*Ausdruck*) and presentation
(*Darstellung*), but also lines, curves, surfaces, carvings, colors, tones,
word sounds, and generally matter or material (*Linien*, *Krümmungen*,
*Flächen*, *Aushöhlungen*, *Farben*, *Tönen*, *Wortklängen*, *Material*)
[@hegel_werke:_1986, *Einleitung*]. The semantic cluster related to "forms"
conveys physical (palpable, of this world) and outward-facing properties,
available for examination to the senses (*Sinne*).

In comparing the dominant aesthetic modes of classical and Romantic periods,
Hegel posits Romanticism as an art that seeks to disengage itself from matter,
reaching the realm of pure self-reflective Spirit. Romanticism, in his words,
is "freed from this immediate existence which must be set down as negative,
overcome, and reflected into the spiritual unity" [@hegel_hegels_1998, 81]. He
writes: "Poetry is the universal art of the spirit which has become free in
itself and which is not tied down for its realization to external sensuous
material; instead, it launches out exclusively in the inner space [*sic*] and
the inner time of ideas and feelings" [@hegel_hegels_1998, 89]. Finally,
"inwardness celebrates its triumph over the external and manifests its victory
in and on the external itself, whereby what is apparent to the senses alone
sinks into worthlessness" [@hegel_hegels_1998, 81]. Romantic art can, in this
way, triumph over the external, material world, reaching, at its apex, what he
calls the stage of "free concrete spirituality" (*freie konkrete Geistigkeit*)
[@hegel_werke:_1986]. The idea overcomes matter to become both free from the
constraints of the deterministic physical universe, yet gaining a measure of
solidity in its tangible instantiation.

Several lines in Hegel's own exposition on Plato's idealism give us a glimpse
of his struggle with the Platonic concept of form. In his "Lectures on
Philosophy," Hegel writes: "The Idea is nothing but what is current with us
under the name of the Universal, when this word is not taken in the sense of
*formal* Universal [*formell Allgemeine*]." The formal universal for him is
"merely a property of things," whereas Plato is concerned with the "implicitly"
universal (as contrasted with explicitly, or formally universal). This internal
"essence" and "in-and-for-itself existent" alone can claim to truth. Hegel
writes: "We translate the Greek word *eidos* by 'genus' or 'species,'" but when
"genus" or "species" are "seized as a number of similar determinations
collected by reflection from several individuals, to serve as a *mark* for the
convenience of the understanding, then we have the Universal in quite an
external form" [@hegel_philosophy_1870, 250]. In other words, as soon as *eidos*
is instantiated, it moves from being an ideal form into an apparent shape, as
an epistemological category.

Someone writes down "all these cats are subsumed under the category of
'feline.'" At this moment, the ideal of "felines" becomes an ossified and
unchanging dead thing. For Hegel, the true ideal must continue to exist and
develop in the real world. It is not merely a socially constructed (we would
say today) category, but something that "internally distinguishes itself" while
remaining "free in its infinitude and independent." The best I can understand
this is to think about the evolutionary process that continues in the species,
even as the taxonomy describing that evolution may remain tied to its fixed
categories. New and radically different cats may come into existence---ones no
longer covered by the "external mark" of being a "feline." Yet this would only
mean that the ideal of "feline" has developed past human understanding.
Zoologists would, at that point, need simply to adjust their categories to
include new forms of feline being. Ideal feline being moves on immediately
thereafter, continuing to develop and leaving behind only the husk or a
"snapshot" of what it meant to be a cat in times already past. For Hegel, one
should not confuse that static snapshot with the animate ideal.

Hegel's "concrete universal" therefore exists in the real, physical world. One
way to understand this difficult concept is to think of it as capturing both
*eidos* and *phantazomenōn*---or idea and appearance, both reasonably
transcribed to "form" in English. The very word "form" in its ordinary meaning
can be, in that way, somewhat a self-antonym. Form could mean "the visible
aspect of a thing," but also the "formative" and the "essential determinate
principle of a thing," and, in its more obsolete meaning, "a formula, model,
type, pattern, and example." Form, in this dual sense, sounds a lot like
Hegel's "concrete universal," encompassing the sometimes contradictory aspects
of the determining and the determined.

These notes on Hegel are not meant to present a definitive history of formalism
in Western aesthetics. Rather, they point to series of related folds or creases
in that tradition, in an arrangement that repeats throughout the vast body of
literature on the topic. The echoes of these complications will resonate later,
within the structure of the document object model, which emerges, in its
stratified form, from the material affordances of screen and magnetic storage
technology in the late 1960s. The question of textual depth then gains an extra
dimension. Where we began with binaries of depth and surface, meaning and
matter, we end with a third: the synthetic document itself that combines
formula and location, shape and thought, conceit and device, where the embodied
meets the ideal.

Generations of critics, from Samuel Taylor Coleridge, W.K. Wimsatt, John Crowe
Ransome, Theodor W. Adorno, and Hans-Georg Gadamer, to Slavoj Zižek, puzzled at
the dual status of literature between the universal and the concrete. For
example, for Coleridge, the excellence of Shakespeare's works consisted in
"that union and interpenetration of the universal and the particular"
[@coleridge_friend_1969, 457]. Wimsatt cites these passages to write that "in
one terminology or another this idea of a concrete universal is found in most
metaphysical aesthetic of the eighteenth and nineteenth centuries"
[@wimsatt_verbal_1954, 72]. Wimsatt concludes by writing that in each
individual poem there is something "which can never be expressed in other
terms." Like irrational numbers, poetry and poetic language for Wimsatt can
only be approached at their limit, not as "all it would be, yet all that can be
had" [@wimsatt_structure_1947, 280]. Hegel's "concrete universal" formula
captures an essential property of literature in its dual movement between the
material and the ideal worlds.

The history of literary scholarship is also punctuated by moments of revolt
against Hegelian reading for latent universalism. A recent conversation on the
merits of surface reading has rekindled an interest in the archeological
metaphor, which understands textuality in terms of depth and surface. Two types
of reading become evident in this model. The "symptomatic" literary critic
reaches beyond the "ephemeral" external appearances to uncover internal and
eternal metaphysical truth within. For a Marxist critic like Terry Eagleton or
Frederic Jameson that latent meaning may have something to do with hidden
machinations of capital and ideology. The psychologically minded critic reads
in search of hidden drives, desires, or cognitive structures. By contrast to
symptomatic reading, Stephen Best and Sharon Marcus describe a constellation of
reading practices concerned with "what is evident, perceptible, apprehensible
in text: what is neither hidden nor hiding; what, in the geometrical sense, has
length and breadth but no thickness, and therefore covers no depth"
[@best_surface_2009, 9]. The authors identify a constellation of related
interpretation practices at the surface: reading for material surface, reading
for verbal structure, reading for affect, reading for description, reading for
pattern, and finally, reading for literal meaning or "just reading."

In the late 1960s, Susan Sontag similarly wrote about "the need for more
attention to form in art." Interpretation can be liberating, she wrote, but it
can also stifle creativity. It "depletes" the world in some way, placing the
critic in a privileged and unnecessarily meddling position between reader and
text. "If excessive stress on content provokes the arrogance of interpretation,
more extended and more thorough descriptions of form would silence," she
writes. "The best criticism, and it is uncommon, is of this sort that dissolves
considerations of content into those of form" [@sontag_against_1966, 8-9].
Marcus and Best remind the reader that Sontag's manifesto is not just an
argument against interpretation, but also an "affective and ethical stance"
[@best_surface_2009, 10]. Strategies of "deep" interpretation carry with them
also a claim to access, and an imbalance of interpretive acumen. The critic
uncovers what the lay reader does not and cannot see. As an ethical stance,
reading for external forms flattens the hierarchy between the lay reader and
the professional interpreter. In this sense, Best, Marcus, and Sontag continue
in the liberal Lutheran tradition of vernacular exegesis. All men are priests
at the surface.

Yet, from the offered strategies of surface reading, reading for form strikes
me as the most ambivalent. It is not clear, for example, what exactly Sontag
means when she entreats her readers to concentrate on "how it is what it is"
and not on "showing what it means." This sort of formalism seems to counteract
the type of surface reading suggested by reading for "literal meaning," for
example. Sontag's "erotics of art" stands in opposition to descriptive,
explanatory, meaning-making modes of analysis. Erotics imply the transmission
of understanding through bodily, lived experience. I understand clearly and
relate to the stance against priestly mediation. But as a positive program,
formalist poetics puzzle me, because "form" already occupies that ambivalent
and mediating stance between idea and matter. Form conforms to the concrete
universal in that it connects physical shape with meaning. One cannot therefore
entirely break out of the hermeneutic circle. Form leads from sense as
perception to sense as meaning-making. Formalist poetics, as I will show in
this section, mirror the ambiguity of form in expanding the literary research
program at once toward the exterior concrete shape and into the inward
universal ideal. Finally, as perhaps yet another gesture towards radical
surface reading, I plan to examine the material structure of contemporary
document at the level of storage media.

But first, to form. In an earlier counterinsurgency against reading for
content, at the turn of the twentieth century, Russian and Italian formalists
strove to break with Hegelian normative aesthetics by wedding literary
criticism with descriptive linguistics. Seeing art as an economy of formal
"devices" like rhyme and meter, the formalists downplayed the role of content
and symbol. In this vein, the Italian futurist Filippo Marinetti wrote about
the "grotesque funeral" of romantic notions of beauty, and the rise of a new
"geometric and mechanical splendor." His generation was instead "in love with
matter," wanting "to penetrate it and to understand its vibrations"
[@marinetti_marinetti:_1972, ???].[^ln4-marinetti] Art cannot be reduced to
"thinking in symbols" Viktor Shklovsky, a prominent Russian formalist, wrote in
1917. Meaning "dies" and "becomes invisible" through frequent use. Such dead
and transparent language can no longer evoke wonder or curiosity. For Shklovsky
and his peers, vital art served to counteract death by "resurrecting the word"
in "making the form difficult" [@shklovsky_hod_1923, ???]. Form, in that sense,
renews content.  The study of poetic language (and not necessarily poetry)
therefore pays attention to device, which aids in the process of semantic
renewal.

Like Sontag, Shklovsky and his fellow members of the "OPOYAZ" group
(instrumental in developing the notion of formalist poetics) were also
responding negatively to the Hegelian tradition of reading for deep, symbolic
interpretation. In a seminal 1917 volume on the "Theory of Poetic Language,"
Osip Brik writes, mockingly:[^ln4-translate]

> "The art of poetry is a symbolic art. The language of poetry is a
symbolic language. Euphony and rhythm are the fair garments that clothe the
fruits of poetic inspiration." That is the solidly established and prevailing
opinion. It is not a surprise then, that the study of poetic structure is
limited to the sphere of obvious euphonic resources like rhythm, alliteration,
assonance, and onomatopoeia [...] Poetic criticism is reduced to the judgment
of "effective" and "ineffective" sound combinations, where the criteria for
effect is reduced to a critic's personal taste [@shklovksy_sborniki_1917, 24].

What do Brik and company see as an alternative to symbolism? The seminal series
of "OPOYAZ" publications, appearing between 1916 and 1920, gave a unified
program to a group of "formalist" scholars that included Viktor Shklovsky, Osip
Brik, Lev Yakubinsky, Boris Eichenbaum, and Roman Jakobson, among others.
Collectively, the volumes strike out in two distinct, but complementary
directions.

A set of essays by Brik, Shklovsky, Yakubinski, and others contrapose "sound"
(*zvuk*) to "symbol" (*obraz*). Brik writes: "I believe that elements of
symbolic and sonic [*zvukovoi*] art exist simultaneously, and that every given
piece of [poetic] work comprises an equilibrium of these two heterogeneous
poetic impulses" [@shklovksy_sborniki_1917, 25]. Of the sixteen or so unique
essays that appear in the three collected volumes (some of the essays repeat
across volumes), thirteen have the word "sound" (*zvuk*), or some variation
thereof, in the title, as "sound image," "sound gesture," and "sound
repetition." To this cluster of essays we may attribute the Russian formalist
concern with *zaum*---literally, beyond sense, or beyonsense
[@khlebnivkov_collected_1987, 179; @khlebnikov_king_1990, 151;
@labelle_lexicon_2014, 63] these are nonsensical sounds that nevertheless
elicit an affective, lived response, giving voice to ideas that are difficult
to explain rationally. Poetry in the symbolic mode encodes meaning as inner
sense: the elephant "stands for" memory, or the like. *Zaum* poetics (beyond
sense) instead evoke affect through external shape, as sound. Khlebnikov
writes that "incantation and beyonsense language are appeals 'over the head'
of government straight to the population of feelings, a direct cry to the
predawn of the soul" [@khlebnikov_king_1990, 152]. Shklovsky defines *zaum* as
"without words but with sound." He writes:

> Thought and speech cannot keep up with inspired experience, and
for this reason artists are free to express themselves not only in language of
common understanding, but also in private language---language that has no
settled sense [...] Lilacs are beautiful, but how deformed [*bezobrazno*] the
word "lilac," plundered and exhausted. This is why I call a lilac "uao,"
restoring its primal clarity [@shklovksy_poetika_1919, 13].

The word *bezobrazno*, in the meaning of hideous or deformed, literally
translates as "without image." The formalists insist on the primacy of the word
image over its sense. They restore the sound image, understanding image not as
"symbol" but as phonetic signature.

Three of the sixteen essays, however, strike in another direction. Shklovsky's
"Art as Technique" and "Linkages between Plot and Style Device," and
Eichenbaum's "How the *Overcoat* Is Made," constitute a cluster of essays that
deals with narrative structure rather than phonetic image. Translators commonly
render the Russian *priem* as the English "device," although both authors
clearly mean "device" in the sense of "technique" or "move,"[^ln4-move] and not
in the sense of "appliance" or "gadget." To this strain of formalism one could
also adduce Vladimir Propp's well-known *Morphology of the Folktale*, a text
that finds a limited number of universal formulas in the multiplicity of
folktale traditions.

All three authors cite a common source of influence: namely, Alexander
Veselovsky, the Russian progressive historian of literature and founder of the
comparative method in that tradition. Veselovsky, a scholar of the generation
previous to the formalists, did not attain the renown enjoyed by his pupils in
the West. An early pioneer of comparative literature, he advocated philology as
a "historical" and "genetic" study of "poetic consciousness and its forms."
Citing literary explorations by Goethe, Friedrich Schiller, and Georges Polti
as his inspiration, Veselovsky almost always uses "form" in the sense of
"formula" (and not at all as "shape" or "sound"). In this, he imagines the
genetic development of literature as the development of universal forms and
devices. He calls these constants "vagabond formulas"
[@veselovsky_sobranie_1913, 185]. He writes:

> Somewhere, someone gave these plots (*siuzhety*) an apt expression, a
> formula, elastic enough to fit, if not new content, then new interpretations
> of plots rich in their associative possibilities. The formula endures.
> Writers will return to it, altering its significance, expanding its meaning,
> and adopting it to new types. As the formula of "desire" was and continues to
> be repeated, so also are repeated the plots of *Faust* and *Don Juan* across
> the distance of centuries [...] We are connected to a tradition. We expand
> within it---not to create new forms, but to attach to them new sentiments and
> concerns. This dynamic could be considered as a type of "law of [cultural]
> energy conservation. [@veselovsky_sobranie_1913, 475-47]

The Hegelian influence is unmistakable in these lines. Like the world spirit,
literary formulae exist and develop across time and space. Veselovsky's formula
is, like a *zaum* incantation, devoid of obvious meaning. It is a container.
But unlike given incantations, formulae have a life of their own, in a trans-
or meta- human way, not accessible to the individual cantor. They can be evoked
but not quite transformed. Their historical momentum and genetic development
overpowers any individual contribution. We expand within *it*, and not the
other way around. Device, in this sense, means exactly the opposite of form in
the sense of a private utterance, by which an individual author breaks with an
ossified image (as in Shklovsky's *uao*).

The contradiction of understanding form as sound and form as formula lies at
the center of formalist poetics. As critics, the formalists privileged moments
of mystic and trans-rational [*zaum*] poetic rebellion against static literary
forms. As literary scholars, they reached for Hegel's concrete universal in
the guise of trans-human formulae that have a life of their own.

Where we started with a dichotomy, we arrive at a tripartite model of
textuality in which form bridges matter and content. The history of Western
aesthetics can be seen as pulling the work of art through one or several of
these layers of analysis: as when Susan Sontag entreats her reader to pay more
attention to form (as sensuous shape), or when Johanna Drucker asks her reader
to consider the materiality of text, or when Sharon Marcus writes about reading
for "what lies in plain sight." But the very words "matter," "form," and
"content" often tangle in the conceptual confusion of texts that resist being
pinned down to any single stratum of interpretation. I am trying to understand,
for example, what Roland Barthes means by the distinction between "work" and
"text" in his seminal essay on textuality.[^ln4-barthes] For Barthes, the work
has something to do with paper, bookshelves, and, more generally, substance. By
contrast, text is something "radically symbolic," something that moves across
works, not bound to any specific matter. Barthes's "texts" sound like ideas,
where his "works" sound like books. This usage stands in direct opposition to
the tradition of textual criticism, where "source texts" stand for specific,
materially-bound editions or manuscripts, and "works" for the collective unity
of the artistic vision: the idea of Shakespeare's *Hamlet*, for example, in
opposition to variance found in the multiplicity of individual *Hamlet*s.

Whereas Barthes wants to liberate text as symbol from the embodied work,
scholars like Johanna Drucker make a strong case for returning the text to its
underlying material contexts. Much of her work reminds the reader that ideas
cannot exist outside of their material form, that paper and typography are the
formal medium for the production of meaning in language, and that even
electronic, digital text formats have their material embodiment
[@drucker_digital_2001; @drucker_graphical_2006; @drucker_letterpress_2008;
@drucker_speclab_2009; @drucker_reading_2013]. I am sympathetic to the message,
but only in so far as it adds a dimension of materiality to a properly
three-dimensional, multi-layered, thick description of text.

A clarification of the terms and an understanding of form both as shape and
formula allows us to perceive the history of textual technology as one of the
gradual stratification between matter, form, and content. Textuality comes
unglued. This allographic property of text---its ability to "peel" away, to
change shape, and to dis-embed---is worthy of critical attention. I am not only
against the theoretical move to batten textuality down, but I think of such
attempts as practically and politically imprudent. The ephemerality of an
electronic text represents the hard-won struggle on the part of writers,
literary scholars, and software engineers to liberate ideas from their material
and formal contexts. As an extreme example, imagine discourse that could never
be separated from a specific medium. Communication would be difficult, if not
impossible! Moreover, deeply seated values in favor of free speech and the
unencumbered exchange of information depend on a loose coupling between
ontological categories. Our abilities to remix, translate, remediate, recycle,
transmit, transform, and transcend the ideas of others relies on their
ephemeral nature. Ideas deposited in ossified matter, in fixed shapes, do not
travel well. And there are plenty of "actors" that would like for culture to
return to the time of singular thought, etched in monolithic tablets, whether
made of stone or silicone.

But, the loose coupling of content to its underlying strata of form and matter
also comes at a cost. As surface phenomena, text hides the flows of power and
control coursing beneath. For now, the text remains if not "at hand," then "at
hand's length." But as books get smaller, "micrographic" writing moves closer
to the optic nerve: first as wearable technology (watches, glasses, pins), then
as ingestible particle (smart dust, nanobots), and finally as something coupled
directly with the nervous system and inscribed into the neural network of the
brain (as the ultimate hard- or rather wetware platform). The movement from
afar to within logically completes the program of "intellect augmentation"---a
program which begins not with Vannevar Bush, J.C.R. Licklider, and Douglas
Engelbart (who used the term extensively), and not with *Xerox*, the ultimate
purveyors of radical surface reading, but with the invention of writing itself.
Reading "for meaning," in these not at all futuristic conditions,[^ln4-reading]
involves turning hermeneutics into reverse engineering.

Form in the sense of "outward shape" suggests an emphasis on what Susan Sontag
deemed the "sensory experience" or the "erotics" of art. In her now classic
1966 essay "Against Interpretation," Sontag posits transparency as the
"highest, most liberating value in art and in criticism today." "Transparency
means experiencing the luminousness of the thing in itself, of things being
what they are" she explains [@sontag_against_1966, 9]. Rather than to show
what a work of art *means*, Sontag urges critics to show "how it is" and "that
it is" [@sontag_against_1966, 10]. To make her argument Sontag relies on the
distinction between "meaning" or "content" on the one hand and "form" or the
"sensory experience" of the work on the other. Form, in this sense, mirrors
McKeown's "shape" and the "text's physical characteristics" of Hayles.

Interpretation at the level of meaning and content for Sontag is an
intellectual and ultimately reactionary activity. It aims to find "the maximum
amount of content" within. It is reactionary because it serves only to
multiply the available "levels of analysis." In explicating the work of art,
the critic essentially creates alternative and diverging copies of the
original. Each layer of critics adds to the content of the work. In Sontag's
words, to "design" a work of art that can be experienced in this way, on
multiple levels, might have been "creative" and "revolutionary" in the age of
aesthetic paucity, when creativity and interpretation were limited to a few
privileged individuals. By contrast, Sontag believes that her times are a
period of creative abundance. "Think of the sheer multiplication of works of
art available to all of us," she writes.  Contemporary culture is based on
"excess" and "material plenitude" which dull the senses. In such conditions,
the production of further critical variations on the theme only adds to the
dulling clutter.

By "interpretation," Sontag means a "conscious act of the mind" which
illustrates a "certain code," or "certain rules" of engagement. It is, for
her, "virtually" a type of translation. The critic "transforms" and "revamps"
the text: X turns out to be A, Y turns out to be B, and so on
[@sontag_against_1966, 3]. And by "form" Sontag means something like the
apparent, perceptual properties of the work: this sentence is long, for
example. And this one short. A critic could say that the sentence length means
something, but Sontag wants to stop short of meaning making. A discipline of
careful perception---of paying attention---rather sharpens the reader's
sensibilities.

The history of interpretation Sontag objects to is one that privileges content
over form. The very words "explication" and "exegesis" imply the movement from
inside to the outside. For a psychoanalytical critic interpretation in that
sense may mean revealing the hidden psychological drives that give rise to a
particular form of an expression. A Marxist critic may instead look for the
concealed operation of this or that ideology. Fredrick Jameson, a prominent
Marxist critic, writes for example:

> Thus the process of criticism is, not so much the interpretation of
content, as it is a revealing of it, a laying bare, a restoration of the
original message, the original experience, beneath the distortions of the
various kinds of censorship that have been at work upon it; and this revelation
takes the form of an explanation of why the content was so distorted and is
thus inseparable from a description of the mechanisms of the censorship itself
[@jameson_marxism_1972, 404].

Although the distinction between form and content is somewhat naturalized in
literary and linguistic discourse, the concept of form is also often used in
another way, which contradict the earlier sense set in opposition to meaning
and content. When we think of Shakespeare's *Hamlet*, for example, whatever is
meant by the "form" of the play belongs neither to its physical medium (pixel
or paper) nor to the ideational content of the work. Form, in that sense, lies
somewhere between the two worlds: it is in the shape of the letters, in the
structure of the narrative, and in the prosody of the word. We do not quite
know which of these elements belong to the content of the play and which are
the contingent material artifacts of the printing process: the way the fonts
look, for example, or the way lines break on the page. Some matters of form
matter to us as readers (line breaks), and others do not (font kerning). Three
things seem to be in play rather than two: matter, form, and content. And of
these, form sometimes falls into the category of meaningless matter and
sometimes into semantic-carrying ideation: form, the indeterminate.

### 4.2 Document Object Model

It is in this tripartite sense of matter, form, and idea that one can best
understand the structure of modern "digital" documents. In the language of the
Document Object Model, the literary-theoretical concept of "form" can mean both
"class" and "instance" (object-oriented programming), or "set" and "object"
(set theory), or "type" and "term" (type theory). Although literature in
computer science rarely operates in the mode of intellectual history,
computer-aided text editors internalized a model of document structure
remarkably similar to the one suggested by Hegelian aesthetics, and in terms of
physical (media), form (formatting), and content (text) levels of analysis. The
Document Object Model weaves the language of the Hegelian universal into the
fabric of modern computing.

Describing *EDIT*, one of the first editors designed for the GE635 36-bit
mainframe computers in use at Bell Labs in 1968, Arthur Kaiman writes: "The
publication editor is divided into three related sections, the document layout
facility, the editing facility, and the printing facility"
[@kaiman_computer-aided_1968, 66]. The "layout," in Kaiman's vocabulary,
contains such things as justification, indentation, and spacing. These
"primitive requests" can be combined to describe more complex "structures of
the printed text." The creators of *QED*, another influential early text editor
(created for the SDS-930 time-sharing system at Berkeley) similarly encourage
the user "to think in terms of structure" of the text. Both *QED* and *EDIT*
begin to separate content and formatting for later recombination and imprinting
onto external storage media. Kaiman explains that "the user types the document
layout file and the text file, then produces a proof or master copy of the text
by printing the text according to the directions of the layout file. The text
file contains layout marks to be interpreted by the layout file." "Text," in
this schema, constitutes content meaningful only to the user, whereas layout
contains some elements meaningful to the human and some elements as code
instructions intended for device control. The notion of "formatting" therefore
mediates between the logical (semantic) and layout (stylistic) structural
representations.

![EDIT Document Model, 1968 [@kaiman_computer-aided_1968, 66].](images/edit.png)

A seminal paper in the field of structured documents proposes the following
model. First, "a document is an object composed of a hierarchy of primitive
objects," write the authors Futura, Scofield, and Shaw. We have two ideas from
the start: composability and hierarchy. A document is a thing made up of other
objects, like sentences and paragraphs. Furthermore, these things stand in a
hierarchical relationship to each other. Paragraphs contain sentences, and not
the other way around, for example.

Second, "each object is an instance of a class." Document level classes include
"letters," "theses," "recommendation," and "papers for a particular journal."
Lower-level classes include sections, paragraphs, footnotes, and so on.

Finally, "objects are further classified as either abstract or concrete." By
this, the writers mean abstract or "logical" objects, like words and ideas. In
describing FORMAT, an important early (circa 1968) "general-purpose" text
processor (written in FORTRAN IV for OS/360 devices), George Berns describes
the program's input as "free-form" (literally, free of form) in that it is
"entirely free of positional restraint [@berns_format_1968, 85;
@berns_description_1969, 141]." Text free of positional restraint, in that way,
can be described in terms of "content," in contrast to "formatted" objects made
"concrete," that is positioned in "one or more two-dimensional *page spaces*
and represent[ing] possible formatted images of abstract objects
[@furuta_document_1982, 417-19; @shaw_model_1980]." The concrete object, in
other words, gives physical shape, layout, or style to the instantiation of
abstract universal classes like paragraphs and sentences. Concrete objects are
abstract paragraphs and sentences "laid out" in page space.

Here is where things should get interesting for a scholar of textuality. The
Document Object Model further gives rise to three "operations," tied to the
"domain and range" of its constituent objects. *Editing*, in this model,
comprises operations that move from abstract to abstract, or, from concrete to
concrete domains.

<!---

+------------------------+--------------+-------------------------------+
| Operation              | Type         | Example                       |
+========================+==============+===============================+
| abstract to abstract   | Editing      | spelling correction \newline  |
| concrete to concrete   |              | move (data) table   \newline  |
|                        |              |                               |
+------------------------+--------------+-------------------------------+
| abstract to concrete   | Formatting   | apply font   \newline         |
|                        |              | break into pages \newline     |
+------------------------+--------------+-------------------------------+
| concrete to abstract   | Recognition  | optical character             |
| \newline               |              |   recognition  \newline       |
|                        |              | page layout analysis \newline |
+------------------------+--------------+-------------------------------+
| concrete to output     | Viewing      | print to paper \newline       |
| \newline               |              | publish to web \newline       |
+------------------------+--------------+-------------------------------+
| concrete to storage    | Filing       | save file    \newline         |
|                        |              | shelve book                   |
+------------------------+--------------+-------------------------------+

Table: Object operation types under the Document Object Model
[@furuta_document_1982, 419-20].

--->

Spelling correction, for example, constitutes an editing manipulation where
abstract objects are modified into other abstract objects. Moving footnotes to
endnotes, or shifting data tables around the document would count as editing of
the "concrete to concrete" type. The authors define *formatting* as giving
concrete shape to ideas in the transformation between abstract and concrete
objects. Italicizing a word, for example, gives the idea of "emphasis" a
slanted form. The act of breaking a document into pages gives shape (and a
specific number of lines, for example) to the idea of a page.

The authors hint at, but do not discuss the opposite movement, from "concrete
to abstract" entities, as would be done in the process of optical character
recognition (OCR). An important part of the digitization process, OCR "lifts"
ideational content from the page image. Without OCR, common document formats
like `.pdf` and `.tiff` therefore remain *merely visual representations*. They
do not, at that stage, contain text or "abstract objects" as such. They are
just pictures. Similar to how humans must "read" a text first in order to
understand it, OCR attempts to "recognize" textual content from the image as a
first step to further manipulation. Leaving aside the question of machine
"understanding," recognition in this case implies more narrowly the
conversation of image into text. This implies also that textuality occupies a
distinct and privileged category in document epistemology, from the point of
view of the machine. Another way to think about machine text would be to
describe "images" as one type of "internal data structure" and text as another,
more "structured" and "more internal," mode of representation. Consider that in
the hierarchical Document Object Model images can contain text, but text
cannot contain images. Text, in that sense, lies at the innermost location in
series of nested "outer" containers. Lacking a model of "comprehension" or
"understanding," the Document Object Model merely posits text as "content" only
in the sense of it being the "innermost" object of recognition.

The "recognition" of characters does not, however, fully capture the variety of
abstract document objects, which besides letters and words include paragraphs,
tables, titles, and footnotes. These also count as "content." It is essential
therefore to know "where text resides on the page," since some elements of
positioning in themselves can carry meaning. For instance, proper names could
carry different connotations depending on their location in the text. A name in
the "author field" means something distinct from any other name mentioned in
the body of the document. Lawrence O'Gorman, an influential researcher in the
field of document image processing, calls the recognition of this sort of
object, at the intersection of concrete and universal, "document lay-out
understanding," which consists of "functional labeling of blocks [...]
distinguished in some way by their physical features (such as by font size) and
by the 'meaning' of the block [@ogorman_document_1993, 1162-63;
@ogorman_document_1995, 82-99 (in the reconstructed edition)]." But note also
that document layout (alternatively "formatting" or the arrangement of
"concrete objects") could also incorporate meaningless (to humans) structures,
such as the incidental "rivers" of empty space formed between the words. That
sort of concrete structure goes "unrecognized" because it does not correspond
to any abstract objects.

![Method for extracting document structure based on "nearest-neighbor clustering
of page components" [@ogorman_document_1993, 1164].](images/docstrum.png)

Finally, the Document Object Model defines *viewing* as the movement from
concrete objects to output device. This could include printing the document
onto paper, or publishing it online, for example. It is at this moment that the
full weight of Hegelian "universal concrete" makes itself known. The "concrete"
object in the Document Object Model is still only a *description* of the
two-dimensional space and represents some "possible formatted images of
abstract objects."[^ln4-dom] To repeat: the concrete object represents
"possible" formatted images, and not yet actual formatted images! To actualize
materially, the document must be fixed and flattened back out onto a medium
such as a screen or paper. These media have actual dimensions. In this way, a
footnote placed at the bottom of the page at the level of concrete object can
then be rendered at the bottom of an A1 (841mm × 1,189mm) size piece of paper
or at the bottom of a much smaller A4-sized sheet (210mm × 297mm).[^ln4-iso216]

In yet another formative paper in the history of contemporary textuality, Brian
Kernighan and Joseph Ossanna describe TROFF, a text processor written circa
1973 for the PDP-11 outputting to Graphic Systems Cat typesetter. In 1979,
Kernighan reports modifying the original program to produce output for a
greater variety of typesetters. Kernighan explains, "TROFF produces its output
in a device-independent form," and its output "must be processed by a drive for
that device to produce printed output" [@kernighan_troff_1992].

This stage flattens out the layers of ideas and visual style, to render them
and to make them visible on screen or page [@furuta_document_1982, 419-20;
@kimura_structure_1984]. Similar to Hegel's "universal concrete," the
"formatting layer" in the Document Object Model bridges the gap between ideas
and matter. Formatting is where ideas connect to physical shape. This is a most
delicate operation, for in giving shape to abstract ideas formatting does
something more notable than mere application of visual style. Formatter
designers from TROFF to FORMAT consistently describe their programs in explicit
terms of instrumental control. Berns, for example, explains that "text control"
as implemented in FORMAT aims to accomplish four "basic" tasks: "to read the
input, to interpret and convert the input as required; to keep the document
flowing smoothly from line to line, column to column, and page to page, unless
otherwise instructed, and to break this automatic flow as directed"
[@berns_description_1969].

Because formatting governs both meaning-carrying and purely decorative
elements, text control can involve operations like "replace word," "make
invisible," or "insert file." These commands intertwine with "free-form"
abstract and ideational content at the formatting level, to come into being in
the "viewing" stage of text processing, where the layers flatten across "a
two-dimensional space" in view of the user. SCRIPT and the related Generalized
Markup Language (GML) developed in the late 1960s by IBM (originally for use on
the CP67/CMS time-sharing system), and now at the basis of ubiquitous XML and
HTML markup languages through ISO 8879, describes a number of such text
transformations that occur to "generate the proper output form." In formatting,
SCRIPT represents the "logical topology" of text in its "canonical form" to
produce an "intermediate data structure," which it then "'unfolds' all at once"
by "'peeling' the data structure one level at a time" [@madnick_script_1968,
97]. As plain text, text control, and user command flows intertwine, the
structure of data on the disk no longer corresponds to what is visible at the
level of user terminal or line printer. Unlike many of the modern text editors,
SCRIPT, TROFF, and FORMAT make all of the laminate components in their
onion-like layered structure available to users for examination. But as we will
see shortly, the condition of complete system visibility persists only for a
short period in history. Once incorporated, the Document Object Model gains a
measure of opacity and even legal protection from "unauthorized access" to
protected innermost document layers.

Whatever model of semiotics one subscribed to in the late 1960s, the DOM fixed
the shape of the sign in accordance to emerging technology. The document object
model continues to structure contemporary text in all its forms: from print
typesetting software to web pages. It gives the material basis to the
conditions of contemporary text production.

!["System Command and Data Flow." Data structures at "disk file" level do not
necessarily correspond to text structures at "user terminal" or "line printer"
levels [@madnick_script_1968, 98].](images/script.png)

### 4.3 Smart Contracts

Exposing the Document Object Model that governs the production of text through
contemporary reading and writing devices gives the question of surface and
depth yet another connotation. What lies beneath the text? We are accustomed to
thinking about document structure metaphorically and answer in accord: meaning,
narrative, representation, order, discourse, or ideology. Interpretation, at
that level of analysis, happens in the head, which physically limits the
possibility of depth to personal introspection, magnetic resonance imaging, or,
at best, to an archive of extant reader responses (which in themselves need
further interpretation).

Incorporating the literary device as machine, gadget, or appliance into the
answer suggests another, more literal strategy of interpretation. Beneath a
text one finds cloth and wood pulp and, increasingly, also glass, plastic,
liquid crystal, copper, laminates, and silicone.

The move between paper and composite device carries with it a profound shift in
the physical affordances of the deep structure supporting all subsequent,
higher-order, surface-level representations of textuality. Not much space
separates ink from paper. There, textuality lies flat, in two dimensions. What
you see is truly what you get. Not so on the screen connected to other screens.
Networked and time-shared textuality extends into the third dimension, away
from the reader and deep into the bowels of the machine. The Open Systems
Interconnection (OSI) reference model of communication[^ln3-osi] describes no
less than seven layers: from the Application Layer, concerned with the
semantics of application ("all services directly comprehensible to the user
[@miller_iso_1981, 285] to the Physical Layer, providing the "mechanical,
electrical, functional, and procedural characteristics" of communication
[@ncs_open_1981; @ncs_national_1988; @day_revised_1995].[^ln3-layers] These
protocols further envelop a document already thickly stratified by the
Document Object Model.[^ln3-domlayer]

[^ln3-domlayer]: The DOM technically exists at the application layer of the OSI
model.

![A zoomed out view of the connected OSI model. Single node structure on the
left. Connected devices on the right. The user has access through the top-most
(application) level, outermost to the network [@piatkowski_iso-ansi_1980,
114-15].](images/osi.png)

These are the same layers that Alexander Galloway unites in a system of what he
calls decentralized and distributed control [@galloway_protocol_2006, 28-54].
It is distributed to be sure, although to what extent decentralized is a matter
of some debate. Like a good soldier, each device in the pictured network
internalizes dozens if not hundreds of protocols that enable the system to
function seamlessly as a whole (in the way, for example, that your machine can
at one moment connect to one wireless access point, and at another moment to
another, with minimal loss of connectivity). Yet, OSI protocols and the DOM are
also densely consolidated. They are, for example, legislated by specific
international governing bodies[^ln3-w3c], susceptible to the usual political
pitfalls of pan-global consortia.

Once bifurcated between storage and screen, the inscription travels along a
"pipeline" of protocols, undergoing a set of arbitrary transformations
throughout. On one device, that pipeline may extend just a few inches,
connecting disk storage and output display. On a network device that pipeline
can stretch across continents, spanning widely divergent regions of legal and
administrative control. The book you are reading here may be stored in another
state or country. Whatever the case may be, the subject encounters the
"protocol stack" from without, on the periphery of the onion-like network. When
paging through an electronic book (usually an OSI-compliant device displaying
DOM-structured files), for example, the reader has access only to the outputs
emanating from the application layer, and, at that, only at the exposed
"window" level of the DOM. The perceived "content" constitutes a small fraction
of the underlying "formal" topology. What you see is far less than what you
get.

The application layer stops at the subject. Access to the layers intrinsic to
device operation (and consequently to analysis) are sometimes "merely" obscured
and sometimes made illicit outright, as is arguably the case with U.S. Code,
Title 17, Chapter 12, §1201, titled "Circumvention of copyright protection
systems" and passed as part of the Digital Millennium Copyright Act (DMCA) in
1998. A literary scholar may be familiar with some provisions of American
copyright law governing text as surface representation: US Code, Title 17
extends "exclusive rights" to "copyright owners" of "literary works." The
rights include the ability to "reproduce," "to prepare derivative works," "to
distribute copies," and "to perform and to display publicly" (17.1.106).
Surface representation is further subject to professional rules of conduct,
embodied in practices of quotation, citation, and attribution (or lack thereof,
as plagiarism).

In practice, the easy reproducibility of digital text (and image) has served to
erode the efficacy of copyright restrictions as a system of laws and
regulations. The work of art in the age of digital reproduction has lost much
of its already tenuous hold on the material substratum.[^ln3-illusion] Copy
technologies from photocopiers, to desktop printers, to cheap magnetic storage
and peer-to-peer file sharing networks reduce the price of copying and
dissemination to near frictionless levels. The response from the film, game,
music, and publishing industries has been to transpose mechanisms of copyright
enforcement from legal down to the infrastructural levels of enforcement, as
software and hardware: from Code to code. In the words of Charles Clark, the
late British publisher and prominent copyright attorney, "the answer to the
machine is in the machine [@clark_copyright_1996, 81-82]"---by which he meant
that copyright enforcement should be taken up on the device level by the
International Standards Organization, the very body responsible for the DOM and
the OSI communication protocol stack [@clark_copyright_1996, 84].

As an example of how that might work, Clark cites the Copyright in Transmitted
Electronic Data Report (CITED), which suggests building "a tamper proof
software module which acts rather like indestructible tachometers installed on
long-distance coaches and lorries, recording everything that happens to the
copyrighted or commercially valuable material [...] The basic idea is to link
the 'valuable material' of intellectual property to a specific piece of
software and hardware" [@consortium_c.i.t.e.d._1994; @clark_copyright_1996,
83-84].

The emergence of embedded contractual enforcement at the level of the device
can be subsumed under the broader idea of "smart contracts." In his seminal
article on "Formalizing and Securing Relationships in Public Networks," Nick
Szabo explains that "smart contracts combine protocols, user interfaces, and
promises expressed via those interfaces to formalize and secure relationships
over computer networks" [@szabo_formalizing_1997]. Clark, CITED, and Szabo were
instrumental in the rise of smart contracts in the 1990s in an attempt to
redress the fading efficacy of legal copyright protections.[^ln3-smart] "Method
and System for Managing a Data Object so as to Comply with Predetermined
Conditions for Usage" (US5845281, issued in 1998) can be instructive in this
regard. Greg Benson and Gregory H. Urich, both of Sweden, write:

> The data object owner may want to have permanent secure control over how,
when, where, and by whom his property is used. Furthermore, he may want to
define different rules of engagement for different types of users and different
type of security depending on the value of particular objects. The rules
defined by him shall govern the automated operations enabled by data services
and networking. The owner may also sell composite objects with different rules
governing each constituent objects. Thus, it is necessary to be able to
implement variable and extensible control.

The data object, in this case, stands for any media content, from books to
music, video, and software. Rather then legislating rules for copying and
distributing media, the inventors suggest that the medium itself should contain
a control layer that would "comply with predetermined conditions of usage," in
a way that can be "universally adapted to the needs of both the owner and the
user of the data object" [@benson_method_1998, 2:55].

!["Concatenated control data and AVI file in memory" [@benson_method_1998].](images/avi-control.png)

!["Concatenated and encrypted control data and AVI file in memory"
[@benson_method_1998].](images/avi-control2.png)

The associated schematics (pictured here) show data and control codes
"concatenated" into the same underlying data structure (in this case, AVI media
container format). The seemingly innocuous "text control" layer of the 1960s,
used to specify formatting and visual style, was now extended to carry
mechanisms for legal control, tied to specific legislation.

The idea of smart contracts contains a notable artifact of implementation,
relevant to our discussion on surface reading. To the extent that control codes
are legible to the interpreter, they are also open to "abuse and
circumvention." For this reason, encryption plays a key part in the smart
contracts system. Once intertwined, data and control must be encrypted to
prevent "unauthorized access." This brings us to the glaring problem at the
very heart of smart contract implementation. The spirit of contractual law by
its very nature demands *explicit* consent. In the language of English common
law, contracts involve promises as "manifestation of intention," which "adopt
an external or objective standard for interpreting conduct
[@american_law_institute_restatement_1973, §1-2.]" The key words in this
passage are "external," "objective," and "interpretation."

By contrast, smart contracts, as described in the patent archive, must rely on
encrypted---that is, not human-legible---forms of tacit compliance: neither
external, objective, nor available for interpretation. The idea of encrypted
consent stands in stark opposition to a tradition of contract law that relies
on models of consent that involve expressed, mutual, explicit, and uncoerced
forms of acquiescence. Even if smart contracts were to be accompanied by
legible documentation (as Terms of Service, for example), the device user would
be compelled to blindly trust in the correspondence between the expressed
letter and the implicit mechanism of the document---the implementation still
enacted beyond scrutiny, as hidden, encrypted, and purposefully illegible
script.

Moreover, the Digital Millennium Copyright Act (DMCA) stipulates that "no
person shall circumvent a technological measure that effectively controls
access to a work protected under this title (17.1201.a.1.A)." The letter of the
law further specifies that to "circumvent a technological measure," in this
case, means "to descramble a scrambled work, to decrypt an encrypted work, or
otherwise to avoid, bypass, remove, deactivate, or impair a technological
measure, without the authority of the copyright owner (17.1201.a.3.A)." A
technological measure that "effectively controls access" is further defined as
a measure that "in the ordinary course of its operation, requires the
application of information, or a process or a treatment, with the authority of
the copyright owner, to gain access to the work (17.1201.a.3.B)." For a
literary scholar, that means that, when encountering a text on a digital
device, reading sometimes *must* limit itself to surface phenomena. An attempt
at reading for depth---to discover the implemented terms of a smart contract,
for example---may carry with it a set of official (even criminal)
sanctions.[^ln3-fairuse]

The short history of DMCA "anti-circumvention" provisions is already littered
with ambiguous case law, that the Electronic Frontiers Foundation believes to
have the effect of "stifling a wide range of legitimate activities," "chilling
free expression and academic research," "jeopardizing fair use," and "impeding
innovation [@von_lohmann_unintended_2010]." Several incidents stand out as
particularly relevant to the study of texts and literature. One, a security
researcher exploring the activity of censorship filters on public library
computers was threatened and forced to seek DMCA exemption from the Librarian
of Congress [@fry_circumventing_2009]. Two, a Russian programmer speaking at a
security conference was jailed and detained for several months for developing
software that converts Adobe electronic book files into `.pdf` format, in a
process that could potentially remove embedded digital rights management
protections [@ferullo_major_2004; @mueller_reinventing_2004;
@postigo_information_2010]. Finally, in 2005 Agfa Monotype Corporation took
Adobe Systems to court in a dispute over the Adobe Acrobat "Free Text" tool,
which allowed users to "change text annotations using Plaintiff's TrueType
fonts" without a license [@_agfa_2005; @lipton_c_2009; @von_lohmann_unintended_2010]. If they become precedent, any of these cases could conceivably
be used to physically limit the efficacy of reading, close and distant.

[^ln3-fairuse]: DMCA 1201 provides for a number of complicated exemptions,
which may, under some interpretations, sanction limited use for academic
purposes. See @liu_dmca_2003; @ku_critique_2004; @herman_catch_2005;
@armstrong_digital_2006.

The impact of DMCA and smart contracts on the practices of reading, writing, and
literary analysis is potentially immense. In the language of the DMCA, the
electronic book is not a book at all, but a "data object," in which the modest
copyright symbol gives way to "control layers [@fischer_digital_2003]." An
essay in the *Yale Journal of Law & Technology* explains it this way:

> While e-books and their print counterparts embody essentially identical
> content, from a transactional standpoint they differ considerably. Books are
> tangible goods that can be owned, sold, and passed on without express
> limitation--the Uniform Commercial Code (U.C.C.) governs their sale, while
> copyright law protects their content. But despite appearances, Kindle e-books
> are not, according to Amazon, sold at all: they are distributed under
> restrictive license terms, similar to downloaded software
[@seringhaus_e-book_2010, 150].

In these conditions, something like a poem or a novel must relinquish its claim
on the universal concrete. In doing that, it ceases to be literature and
becomes instead a device, firmly tied to its given physical affordances.
Reified as a concrete object, no longer lasting and universal, but rather
ephemeral and contingent, it is subject to the whims of the market. The device
now gains the ability to dynamically adapt itself "to the needs of both the
owner and the user." These adaptations could of course take a benign form, of
the kind suggested in "*Remix: Literatur*," where Michel Chaouli imagines a
device akin to a "literature equalizer," empowering readers to "tune" any given
text to their liking [@chaouli_remix_2009]. Don't really like intensifiers?
Just turn the "adverb knob" down! I hold on to the possibility of building such
a device with Chaouli. In the meantime, existing electronic book software and
hardware devices adapt themselves to the reader in less creative ways. Some
prevent simple copy and paste actions. Others can be used to censor and
surveil. For a textual critic, such instability of medium means analysis cannot
be confined to reading for surface meaning alone. How can close or distant
reading practices persist, when the reading device reconfigures a text
dynamically, to fit individual taste, mood, or politics?[^ln3-modern] Or, when
it simply prevents access to some of the content?

[^ln3-modern]: Note that these effects are not limited to contemporary
literature at all. In purchasing a medieval text, the reader still buys not a
text or a work but a device, which, despite the content being out of copyright
protection, may still restrict access to other, protected layers of device
function.

Smart contracts and DMCA are a conspicuous symptom ailing all text gadgets,
which offer only the illusion of flat textuality. Where a literary scholar
could hope to gleam the machinations of ideology from surface representation in
print, the literary device obscures literal flows of governance. Isomorphic
application design makes the situation worse in giving a measure of similarity
between page and screen (the definition of isomorphism), obscuring material
divergence beneath. The condition is not one of ephemeral, immaterial text, but
one of text burdened with hardware and illegible control structure. The task of
the critic becomes then to restore text to its proper mode of being in the
concrete universal: to give it permanence in the world of ideas and to free it
from its arbitrary material constraint. To lay bare the device literally would
mean to make the mechanisms of naked political control visible. For any sort of
reading to commence, one would first need to peel away the DOMs and the
OSIs---today a task fraught with legal consequence.


Essential for the practices of unencumbered critical thought, control
structures exist in the gaps within the splintered sign. Ultimately, parts of
the inscription that remain invisible affect more than typesetting
characteristics. They shape the very structure of interpretation. The
seemingly innocuous control and formatting layer contains the essence of
machine control. Long a marginal concept in literary theory, formatting is
therefore central to the practice of computational hermeneutics. Far from mere
inconsequential embellishment, formatting governs the interface between
meaning and matter, thought and page. It has the capability to embellish, to
obscure, to censor, to govern, and to emend.

The attached documents illustrate my thesis in practice. In the first image
the reader will find a visual "dotplot" representation of Laurence Sterne's
*The Life and Opinions of Tristram Shandy*, in plain text (`.txt`) file
format. To produce the image, I use the Helfman's self-similarity dotplot
approach. Dotplots, as Helfman explains, "reveal similarity structures in data
regardless of format and in text and software regardless of language"
[@helfman_dotplot_1996]. They can be used for authorship identification,
plagiarism detection, or to find similarity in genetic material. The
following, is a simple dotplot from Shakespeare:

+----+---+---+---+----+---+---+
|    |to |be |or |not |to |be |
+====+===+===+===+====+===+===+
|to  | • |   |   |    | • |   |
+----+---+---+---+----+---+---+
|be  |   | • |   |    |   | • |
+----+---+---+---+----+---+---+
|or  |   |   | • |    |   |   |
+----+---+---+---+----+---+---+
|not |   |   |   | •  |   |   |
+----+---+---+---+----+---+---+
|to  | • |   |   |    | • |   |
+----+---+---+---+----+---+---+
|be  |   | • |   |    |   | • |
+----+---+---+---+----+---+---+

Table: "Six words of Shakespeare" [@helfman_dotplot_1996].

When applied to raw, binary data, self-similarity plots can be used to study
data structures, to identify security threats, and to reverse engineer unknown
file types. Note that, at this level, we are not observing patterns of meaning
(as repetition of words or word clusters), but rather structural patterns in
the underlying bit structure. We cannot tell from the image what these
structures mean, only that they have a particular shape. Structure, in this
sense, indicates architecture by human hand. We expect random data to render
into undifferentiated patternless noise. By contrast, file formats, like the
common `.docx` and `.mobi` files, will leave a recognizable signature, even
when corrupted. The sparse topography of the `.txt` file in the first image
indicates a relative paucity in bit types.  Plain text formats are limited to
human-legible UTF-8 or ASCII character sets (used to to encode the `.txt`
file). The square on the lower right likely represents lower case letters,
with the other two squares showing capitals and punctuation.

The second image (Fig. 12) shows the same novel encoded into the popular
Mobipocket (`.mobi`) book format, used to store books on an Amazon Kindle
device, for example. While the plain text signature is still present, other
structures now also come into view. These are not human-legible under closer
examination (using a hex-editor for example) because the data is encrypted.
The plain text characters remaining comprise snippets of code, and some light
header and footer information, identifying the file to reader applications.

To produce the third image (Fig. 13), I encode the plain text version of the
novel into the Portable Document Format (`.pdf`), another commonly circulated
binary format for document storage. In an additional step, I use code
injection techniques outlined in @rahman_getting_2010,
@stevens_malicious_2011, and @maiorca_looking_2013 to introduce a malicious
script into the header of the file. Depending on the version of the reader's
Adobe Acrobat Reader, the code will execute when opening the document, with
the potential of causing significant corruption to the system. The injection
is clearly visible in the image, manifesting as a "cavity" of un-encrypted
characters. Steps could be taken to further mask the malicious script,
blending it with the background encrypted bit structure (shown as speckled
noise), which would make the injection more difficult to detect.

!["Binary file structure I." Laurence Sterne's *Tristram Shandy*, in `.txt`
format.  Unaltered.](images/txt.png)

!["Binary file structure II." Laurence Sterne's *Tristram Shandy*, in `.mobi`
format.  Unaltered.](images/mobi.png)

!["Binary file structure III." Malicious code injection into the text of
Laurence Sterne's *Tristram Shandy* in `.pdf` format. Cavitation indicating
presence of injected code.](images/pdf.png)

In conclusion, I do not mean to imply that the "closest possible" reading of
this sort, at the circuit and magnetic storage level, will somehow come to
supplement reading at the surface for meaning and representation.
Microanalysis is meant to complement close reading: giving it proper scope in
time and space for its operation. But reading at the surface alone also risks
losing sight of the naked struggle for power and control at the device level.
The machine *can* determine the message when unchecked. In these conditions,
reading without depth may struggle to even locate its object of study, as
surface representations change dynamically, tailoring themselves to fit the
reader's mood, to match the environment, or to please some remote censor.
Best, Marcus, and Sontag are right in treating claims to symptomatic reading
with suspicion, as claims to power. The reader of depth divines secret
knowledge, with or without merit, creating an imbalance of interpretation.
Critical reading in all dimensions must therefore begin with the ethics of
mutual legibility. It succeeds when readers reclaim the underlying material
conditions of their meaning making. The very architects of the "smart"
literary device tell us: the answer to the machine remains in the machine.

<!-- notes -->
<!-- notes -->
<!-- notes -->

[^ln4-dom]: See @furuta_document_1982, 418: "Concrete objects are defined over
one or more two dimensional page spaces and represent possible formatted images
of abstract objects."

[^ln4-iso216]: A series of paper sizes are governed by the International
Standard ISO 216. In the Imperial System these equate to 33.1in × 46.8in and
8.27in × 11.7in respectively
[@international_organization_for_standardization_writing_1975].

[^ln4-move]: "Move" in the sense that *Harai Goshi* is a "Sweeping Hip Throw"
"move" in Judo, and a part of *Koshi-Waza* or "hip technique."

[^ln4-illusion]: Matthew Kirschenbaum puts it this way: "Computers are unique
in the history of writing technologies in that they present a premeditated
material environment built and engineered to propagate an illusion of
immateriality; the digital nature of computational representation is precisely
what enables this illusion---or else call it a working model---of immaterial
behavior" [@kirschenbaum_mechanisms_2012, 135].

[^ln4-mechanisms]: In this approach I build on the work by @galloway_protocol_2006;
@conti_visual_2008; and @kirschenbaum_mechanisms_2012.

[^ln4-root]: @stoltz_is_2013

[^ln4-osi]: Drafted in 1978 as ISO/TC97/Sc17/N46 and adopted by the
International Organization for Standardization in 1984, as ISO 7498.

[^ln4-layers]: The full OSI protocol stack includes Application, Presentation,
Session, Transport, Network, Data Link, and Physical layers
[@piatkowski_iso-ansi_1980; @miller_iso_1981; @ncs_open_1981; @day_osi_1983;
@day_revised_1995].

[^ln4-smart]: For examples see @grundy_information_1994;
@kaliski_abuse-resistant_1995; @hasebe_licensee_2003.

[^ln4-plato]: My reading of Plato would be impossible without help from the
Perseus Digital Library Project, which allows the reader to explore the Greek
originals side-by-side with translations, maps, dictionaries, and other
parallel texts. Sources consulted on Plato's theory of forms include
@hegel_philosophy_1870; @rist_platos_1975; @dixsaut_ousia_1991;
@woods_form_1993. I would also like to thank Stathis Gourgouris for his
generous comments on these passages.

[^ln4-reading]: All of the technologies I list here exist today (in the second
decade of the twenty-first century) commercially, much beyond the prototype
stage.

[^ln4-translate]: Translations are mine, unless cited otherwise.

[^ln4-barthes]: "The work is a fragment of substance," he writes. The work is
"moderately symbolic" where text is "radically symbolic." The work "occupies
space of books," where the text is "a process of demonstration," "experienced
only in an activity of production." He writes also that "the Text cannot stop
(for example, on a library shelf); its constitutive movement is that of cutting
across (in particular, it can cut across the work, several works)"
[@barthes_work_1978, 156-7].

[^ln4-descartes]: It is difficult to resist quoting from Descartes's
*Meditations on First Philosophy* when discussing idealism. He writes: "Let us
consider the things that people ordinarily think they understand best of all,
namely the bodies that we touch and see. I don't mean bodies in general---for
our general thoughts are apt to be confused---but one particular body: this
piece of wax, for example. It has just been taken from the honeycomb; it still
tastes of honey and has the scent of the flowers from which the honey was
gathered; its color, shape and size are plain to see; it is hard, cold and can
be handled easily; if you rap it with your knuckle it makes a sound. In short,
it has everything that seems to be needed for a body to be known perfectly
clearly. But as I speak these words I hold the wax near to the fire, and look!
The taste and smell vanish, the color changes, the shape is lost, the size
increases; the wax becomes liquid and hot; you can hardly touch it, and it no
longer makes a sound when you strike it. But is it still the same wax? Of
course it is; no one denies this. So what was it about the wax that I
understood so clearly? Evidently it was not any of the features that the senses
told me of; for all of them---brought to me through taste, smell, sight, touch
or hearing---have now altered, yet it is still the same wax."

[^ln4-marinetti]: "Il nostro amore crescente per la materia, la volontà di
penetrarla e di conoscere le sue vibrazioni, la simpatia fisica che ci lega ai
motori, ci spingono all'uso dell'onomatopea." [from Lo splendore geometrico a
meccanico e la sensibilità numerica]

[^ln4-echenbaum]: "Что касается 'формы', то формалистам было важно только
повернуть значение этого запутанного термина так, чтобы он не мешал постоянной
своей ассоциацией с понятием 'содержания', еще более запутанным и совершенно
ненаучным" [@echenbaum part3 of Teoria Formalnogo Metoda]

[^ln4-translate2]: "In our discussion of this text we have been using an
authoritative French translation of Plato, the one published by Guillaume Bude.
In the case of *Phaedrus*, the translation is by Leon Robin. We will continue to
refer to it, inserting Greek text in parenthesis [@derrida_dissemination_1981,
71]."

[^ln4-gurevich]: Kittler mistakingly attributes "Algorithms in the World of
Bounded Resources" to Brosl Hasslacher. The author is rather Yuri Gurevich,
Principle Researcher at Microsoft Research and then a professor at the
University of Michigan. Hasslacher's essay entitled "Beyond the Turing Machine"
appeared in the same volume of collected essays, @herken_universal_1988.

[^ln4-bottom]: For example, in the Open Systems Interconnection (OSI) model of
communication, the top-most layer of protocols and interface method is called
the "application layer" and the bottom-most layer the "physical layer"
[@peterson_computer_2007, 26-28]. Timothy Colburn and Gary Shute describe it as
being "responsible for encoding bits onto a transmission medium, whether wires,
fiber optics, or radio broadcast, in ways that maximize the transmission rate
and minimize sensitivity to noise [@colburn_abstraction_2007, 181].

[^ln4-abstraction]: This is a topic of some contention in the literature. In
his influential paper on the topic, James Moor includes the immateriality of
software as one of the "three myths" of computer science. "As a practical
matter, what we regard as computer instructions, and consequently what we
regard as computer programs, is determined by computers available," he writes
[@moor_three_1978, 215]. Nurbay Irmark argues that software is instead a purely
abstract artifact, akin to a musical work [@irmak_software_2012]. See also
@turner_programming_2013; @colburn_software_1999.

[^ln4-turing]: The intellectual history of the Turing machine is well
established, in multiple works on the subject. It follows the Greek Diophantus,
René Descartes, Georg Cantor, David Hilbert, Gottlob Frege, Bertrand Russell,
Kurt Gödel, Ludwig Wittgenstein [@petzold_annotated_2008;
@herken_universal_1988; @grattan-guinness_development_1981].

[^ln4-alt]: "We have to think (in a completely novel way) the relation between
a science and the ideology [...] the fact that such an investigation confronts
us with the observation that every science, in the relationship it has with
ideology it emerged from, can only be thought as a 'science of ideology, would
disconcert us, were we not forewarned of the name of the *object* of knowledge,
which can only exist in the form of ideology" [@althusser_reproduction_2014,
46].

[^ln4-derr]: See @derrida_writing_1978. I am alluding particularly to
statements like "ethnology-like any science-comes about within the element of
discourse," and "this moment was that in which language invaded the universal
problematic; that in which, in the absence of a center or origin, everything
became discourse-provided we can agree on this word-that is to say, when
everything became a system where the central signified, the original or
transcendental signified, is never absolutely present outside a system of
differences. The absence of the transcendental signified extends the domain and
the interplay of signification ad infinitum" (278-294).

[^ln4-flip]: There is a long-standing joke in Marxist literature that involves
flipping Hegel, who prioritized the transcendent spiritual over the physical
and material forms of life, over "back to his feet." See for example
@marx_marx-engels_1978: "The form of wood, for instance, is altered, by making
a table out of it. Yet, for all that, the table continues to be that common,
every-day thing, wood. But, so soon as it steps forth as a commodity, it is
changes into something transcendent. It not only stands with its feed on the
ground, but, in relation to all other commodities, it stands on its head, and
evolves out of its wooden brain grotesque ideas, far more wonderful than
'table-turning' ever was" (320). See also @engels_ludwig_1941: "Thereby the
dialectic of the concept itself became merely the conscious reflex of the
dialectical motion of the real world and the dialectic of Hegel was placed
upon its head; or rather, turned off its head, on which it was standing
before, and placed on its feet again" (44).  p5


[^ln3-w3c]: The International Standards Organization (ISO) in the case of OSI,
the Internet Engineering Task Force in the case of TCP/IP, and the World Wide
Web Consortium (W3C) in the case of the DOM.
