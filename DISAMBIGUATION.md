# Disambiguation and Open Access

Initially Shared: January 18th, 2021; Updated: April 28th, 2021

Open Function Group (“OFG”) builds and maintains a large-suite of open-source
and proprietary software for governments and NGOs around the world, provides
hosted use of that software, and consults on data integration projects. The
major offerings, both proprietary and open-source, can be used independently or
in concert with one another.

![Open Access Commitment_wbg](https://user-images.githubusercontent.com/8732845/116373445-402e2180-a805-11eb-9dc6-11d3bd99cfe3.png)

## Disambiguation around OpenFn’s Products

1. “platform” is the proprietary, enterprise integration-platform-as-a-service
   offering from OFG. (N.B., It can be hosted on the cloud or deployed locally,
   and it has both free and paid tiers, but it is closed-source.)

2. “core” is the open-source program that is used to run integration jobs.

3. “adaptors” are the open-source modules which provide tighter connectivity
   with key tools across ICT4D.

4. “microservice” is the open-source job coordination, initiation, and logging
   program developed as a prototype by OFG in partnership with DIAL’s OSC and
   UNICEF.
   
5. "engine" is the open-source job runner that makes use of "core" and the
   "adaptors" and is used by _both_ "platform" and "microservice".

## The Digital Square E0 Grant

Excepting “WP3 - Enhanced Installation Support”, all E0 funding will go towards
the development, enhancement, and documentation surrounding our open-source
products and they will not be used to further develop platform.

To ensure the long-term sustainability of engine, we’re proposing to design and
license it in such a way that it can both be used as a standalone solution, within
"microservice", or as a module in platform (or any other software, yet to be built
by OpenFn or others).

- This is how we’ve designed and licensed core and our adaptors. By selecting
  the LGPL license, we can ensure that any derivative works remain open-source,
  but those works which include engine (as a module) may themselves be
  closed-source.

- As has been the case with core and adaptors, this will further ensure that as
  OFG invests in platform it will be incentivized to continue investing in
  engine without relying on securing repeat grants.

For “WP3 - Enhanced Installation Support”, OFG has proposed building a new
feature in platform (see “button” in diagram) which will be “open access” in the
sense that it’s freely available, but it will not be functionally open-source
because it will depend on the proprietary platform to run.

- This feature will be available to any user on the platform free tier and will
  allow them to export a project configuration from platform to run as a
  standalone implementation of microservice.

Over time, we expect that by (a) sustaining OFG’s SaaS business by keeping
platform closed-source, (b) incentivizing OFG to invest in engine over the
long-term, independent of grant funders, and (c) by making the process by which
users can shift from platform to engine more streamlined, we’ll see increased
adoption of engine and greater success in health integration and
interoperability projects globally.
