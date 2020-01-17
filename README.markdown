# Remote-Led Companies

This is a list of companies that employ remote leaders along with data about
how far away from an office they are allowed to work.

## Metrics

Two metrics for gauging the efficacy of a remote work environment are:

* Do leaders (at least some of them) usually work from home? Having leaders who
  primarily work at home is a good indicator the remote work environment will
  be inclusive and that effective communication between leadership and remote
  workers is transpiring.

* Are leaders required to work near a physical office? This is a good indicator
  of the level of company commitment to distributed teams as well as chances of
  promotion. A remote job is great but not being able to advance unless you
  move across the country really makes it just a job; some people would prefer
  to have a remote career.

There are plenty of other metrics we could use, but after fifteen years of
working remote I feel everything else can be seen as falling out of these two
culture-level metrics. If you have the right culture all the other bits are
implementation details that can be reasonably expected to change to better
serve that culture.

## Why Leaders?

My experience has been if the culture supports off-site leaders there is a
genuine remote-first culture with transparent group communication. If leaders
must be colocated then significant discussions happen in face-to-face meetings,
over lunch and after work from which remote employees are always excluded. A
lack of remote leadership can also be an indicator that senior leadership is
just tolerating remote and given a chance would shut it all down.

## Proximity Key

| Code | Definition | Description |
| --- | ------- | - |
| `C` | C-Suite | |
| `V` | VP | |
| `D` | Director | |
| `M` | Manager | |
| `*` | anywhere | adequate Internet connection |
| `mh` | medium haul | ~3000-mile flight range |
| `na` | north america | North America only |
| `do` | domestic | same country as an office |
| `tz` | time zone | within (a) certain time zone(s) |
| `dd` | driving distance | few hours drive of an office |
| `ma` | metro area | same metro area as an office |

Use `do` if roles are definitely remote but no proximity information is
available.

## Format

Company | Headquarters | Other Offices? | Proximity  
RemoteCo | San Francisco | Yes | `M* Ddd`

Company is the company name. Headquarters is the location of the company
headquarters--or None. Other Offices? is meant to be Yes/No rather than a list
of the other offices.

Generally we assume that all levels underneath a given level are at least as
permissive with regards to Proximity, so if a company’s VPs (and below) can
work from anywhere but C-Suite has to stay within driving distance its
proximity would be `V* Cdd`. If a company only allows managers and directors to
work remote and they have to live in the same country as an office its
proximity would be `Ddo`. A fully remote company with no co-location
requirements for any role—perhaps no physical offices at all—would have a
proximity of `C*`.  Multiple codes may be used for expressiveness—a company
that allows managers to work remote in the Pacific time zone of the US only
would have a proximity of `Mtzdo`.

Proximity describes the most permissive case, so if there is only one org
within an large company that allows its managers and directors to work from
anywhere the whole company still has a proximity of `D*`. However, an
individual being allowed to work remote in a role that otherwise would not be
remote—a VP who tried to quit to move to France so they let her work remote,
say—does not count. If a company definitely has remote managers but no
proximity information is known, use `do`—such a company would have a proximity
of `Mdo`.

## Contributing

PRs that remove a company or “downgrade” one to a less permissive proximity
(`Ddo` -> `Dma`, say) will be rejected unless they come from am employee of
that company. This is to prevent folks from trying to modify a company’s status
because they are unable to find a current supporting job listing.

## The List

| Company | Headquarters | Other Offices? | Proximity |
| ------- | ------------ | -------------- | --------- |
| [Airbase](https://www.airbase.com) | San Francisco | Yes | `Ddo` |
| [Auth0](https://auth0.com) | Bellevue, WA | Yes | `C*` |
| [Axios](https://axios.com) | Arlington, VA | Yes | `Ddo` |
| [Basecamp](https://basecamp.com) | Chicago | No | `C*` |
| [Canonical](https://canonical.com) | London | Yes | `M*` |
| [Cinchapi](https://cinchapi.com/) | Atlanta | No | `Mdo` |
| [Citrine Informatics](https://citrine.io) | Redwood City, CA | Yes | `Mdo` |
| [Clipboard Health](https://www.clipboardhealth.com) | San Francisco | No | `Vdo` |
| [ConvertKit](https://convertkit.com) | Boise, ID | No | `Mdo` |
| [DataStax](https://www.datastax.com) | Santa Clara, CA | Yes | `Mdo` |
| [DockYard](https://dockyard.com) | Boston | No | `Ddo` |
| [Eager Labs](https://www.eagerconnect.com) | None | No | `M*` |
| [Elite HRV](https://elitehrv.com) | None | No | `Cdo` |
| [Etsy](https://www.etsy.com) | NYC | Yes | `M*` |
| [Fastly](https://www.fastly.com) | San Francisco | Yes | `C*` |
| [GatsbyJS](https://gatsbyjs.org) | Berkeley, CA | No | `Mdo` |
| [Ghost](https://ghost.org) | None | No | `C*` |
| [GitHub](https://github.com) | San Francisco | Yes | `Mdo` |
| [GitLab](https://gitlab.com) | San Francisco | No | `V*` |
| [Help Scout](https://www.helpscout.com) | Boston | Yes | `M*` |
| [InVision](https://www.invisionapp.com) | None | No | `C*` |
| [Lesbians Who Tech](http://www.lesbianswhotech.org) | None | No | `Cdo` | 
| [Olo](https://www.olo.com) | NYC | No | `Mdo` |
| [Parse.ly](https://www.parse.ly) | NYC | No | `C*` |
| [Plaid](https://plaid.com) | San Francisco | Yes | `Dtz` |
| [ReCharge Payments](https://rechargepayments.com) | Santa Monica, CA | No | `Mna` |
| [Redox](https://www.redoxengine.com) | Madison, WI | Yes | `C*` |
| [Theorem](https://theorem.co/) | Los Angeles | Yes | `Mdo` |
| [Twitter](https://twitter.com) | San Francisco | Yes | `Mdo` |
| [Walmart Labs](https://www.walmartlabs.com) | San Bruno, CA | Yes | `Mdo` |
| [Wikimedia Foundation](https://wikimediafoundation.org) | San Francisco | Yes | `C*` |
| [Wirecutter](https://thewirecutter.com) | NYC | Yes | `Ddo` |
