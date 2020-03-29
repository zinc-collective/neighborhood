# Neighborhood

_It's our world. Not Zuckerberg's._

### Made on Main Street, Not Market Street

Neighborhood is community-source software. We're not owned by private banks or
billionaires. Neighborhood is 100% owned by our Contributors, Operators and
Residents.

### You are Now Free to Move About The Internet

If your chosen Neighborhood isn't reliable or safe, it's easy to move to a
different one. All of your writing, photos, videos, interactions, and
relationships are securely portable. Once you've moved, you can remove your old
data and leave a public forwarding address.

### Not Just Sustainable, Restorative

Neighborhood is designed to be socioeconomically restorative. We incorporate
restorative justice principles and practices into our operating agreement, our
culture, our design, and our code itself.

## Design

Neighborhood's design goal is to encourage Mr. Rogers like experiences on the
web. Kindness, not civility. Firmness, not cruelty. We believe such a social
network must prioritize designing for professional operators build and maintain
trust, set and maintain healthy boundaries, and can make a living wage while
doing it.

### Experience Design

Neighborhoods are composed of personal, social or commercial Spaces. These
Spaces are connected by the Sidewalk, where the hustle and bustle of the
Neighborhood streams as Events happening within a Resident's Sphere. Residents
may adjust their Sphere to ignore incoming or block outgoing Events.

### Fauxsona Map

> Note: None of these are researched or defined enough to be real Personas.

| Fauxsona    | Jobs                                                              | Goals                                                                                      |
| ----------- | ----------------------------------------------------------------- | ------------------------------------------------------------------------------------------ |
| Operator    | Maintains social and technical infrastructure for the Neighborhood | Facilitate mutually beneficial socioeconomic relationships for communities they care about |
| Resident    | Participate in genuine, socially-considerate way                  | Better health through affirming, healthy connections.                                      |
| Contributor | Make structural changes to the Neighborhood platform              | Develop their skills, make Neighborhood support their use cases.                           |

### Architecture

Our architectural priorities are:

1. Diverse, wide, warm community.
2. Stable, reliable release cadence.
3. By and for small, cohesive groups.

## Privacy- hard rules not soft talk

### Legal realities vs User expections
Currently you leave a trail of digital breadcrumbs wherever you go:
* server logs and URLs accessed (permanent history in some cases);
* browser tracking via web-bugs and double-dereferencing;
* cross-site cookies allows correlation of user profiles;
* and we haven't even started on geotagging, AI user correction, or [ghostjacks](https://www.zdnet.com/article/tech-giants-and-civil-liberty-groups-call-out-ghost-cops-and-source-code-demands-under-australian-encryption-laws/).

Some famous US caselaw (incomplete):
1. Roe v. Wade (1973) 
2. Lawrence v. Texas (2003)

Modern expectations are:
* limit physical or electronic intrusion into one's private quarters;
* forbid the dissemination of truthful private information which a reasonable person would find objectionable
* the publication of facts which place a person in a false light, even though the facts themselves may not be defamatory
* the unauthorized use of a person's name/likeness/identity to obtain some benefits

### Relevance for Zinc Coop
As a Californian LLC, Zinc is bound ultimately to follow California Consumer Privacy Act ([CCPA](https://en.wikipedia.org/wiki/California_Consumer_Privacy_Act)) which mirrors EU's General Data Protection Regulation ([GDPR](https://en.wikipedia.org/wiki/General_Data_Protection_Regulation)) with opt-out. The basic thrust is to give web users the ability to see what information is collected about them and stop that data from being sold. In addition there is a [privacy tort](https://en.wikipedia.org/wiki/Privacy_laws_of_the_United_States) which affirms the right of seclusion. For a warm community to develop trust and sharing without shame, the design must/should from the start support:
* Right to rebuttal - if someone talks about you, should be able to respond in a civil manner;
* Social Capital	- if reputational has a certain social credit (eg for being civic) then more powers could be granted;
* Right to be Forgotten - what you say, do or act can be eraseable (eg blank slate for old misdemenors);
* Moral Right to be Forgiven - sometimes even if a deed is immemorial, forgiveness shoud always be an option as part of restorative justice.

# Implementation

For the frontend, we rely on [Tailwind UI][tailwind-ui].

For the backend, we rely on [Ruby on Rails][rails].

[tailwind-ui]: https://tailwindui.com/
[rails]: https://rubyonrails.org/
