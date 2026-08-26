# LUP4LDN

**Land Use Planning for Land Degradation Neutrality**

LUP4LDN is a geoinformatics and participatory land-use-planning tool that
helps national and local planners assess land-use and land-management
transition scenarios, identify restoration priorities, and evaluate the
suitability of sustainable land-management interventions in support of Land
Degradation Neutrality (LDN, SDG Indicator 15.3.1).

🌐 Live tool: **https://www.landusetool.org/**

## Origin

LUP4LDN won the **GEO-LDN International Technology Innovation Competition**
in 2021 ([UNCCD announcement](https://www.unccd.int/news-events/geo-ldn-competition-winner-announced)),
developed by a multi-institutional team led by **SCiO**, with contributions
from ICARDA, the University of Sassari, WOCAT and the ELD Initiative. SCiO
has continuously maintained and operationally supported LUP4LDN since the
award.

The tool's methodology is documented in a peer-reviewed publication:

> Zucca, C., Le, Q.B., Karampiperis, P., Lemann, T., Thomas, R.,
> Thiombiano, B.A., Hermassi, T., Bonaiuti, E., Zervas, P. (2024).
> *Toward an operational tool to integrate land degradation neutrality into
> land use planning: LUP4LDN.* Land Degradation & Development, 35(7),
> 2489–2507. https://doi.org/10.1002/ldr.5075

## Repositories

This is an umbrella/index repository. The application code lives in two
component repositories:

| Component | Repository | Stack |
|---|---|---|
| Backend API | [`SCiO-systems/landusetool-backend`](https://github.com/SCiO-systems/landusetool-backend) | Laravel (PHP) |
| Frontend dashboard | [`SCiO-systems/landusetool-frontend`](https://github.com/SCiO-systems/landusetool-frontend) | React (Diamond-React) |

Each component repository has its own README with setup and deployment
instructions. To run LUP4LDN locally, start the backend first (it exposes
the API the frontend consumes), then the frontend with its
`REACT_APP_API_BASE_URL` pointed at your local backend.

## License

LUP4LDN is open-source software, licensed under the
**GNU General Public License v3.0** — see `LICENSE` in each repository.

## Use and recognition

- Featured in the UNCCD Science-Policy Interface report on Integrated Land
  Use Planning (Box 5.1).
- Referenced in the GEF-funded Tools4LDN project.
- Selected by the FAO Investment Centre (2026) among tools reviewed for
  ecosystem-service valuation in agricultural investment design.
- Co-developed and piloted with INRGREF (Tunisia) and IDR-UNB (Burkina
  Faso); in active use across nineteen municipalities in Senegal (2026).

## Contributing

See `CONTRIBUTING.md` in each component repository. Please report security
issues privately per `SECURITY.md` rather than opening a public issue.

## Contact

**lup4ldn@scio.systems** · maintained by [SCiO](https://scio.systems/)
