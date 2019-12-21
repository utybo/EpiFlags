# EpiFlags

EpiFlags is a repository which contains source SVG files for logo and logo 
concepts for EPITA International servers.

## The servers

In the fourth semester at the "EPITA" school, students go abroad in many 
countries. In order to better organize themselves, the students have created
Discord servers, and these servers have logos which are inconsistent or straight
up... not nice.

## Copyright notice

The logos and all other files in this repository are made available under the CC
BY-NC 4.0 International license. You can read a
[human-friendly version](https://creativecommons.org/licenses/by-nc/4.0/) or
the [license's text](LICENSE).

The EPITA logo embedded in all flags was recreated from the ground up. This
project is not endorsed by the EPITA school. The EPITA logo may be a registered
trademark, please inform yourself!

**If you are a EPITA student maintaining one of the aforementioned servers**, 
you are free to use the corresponding logo for the server.

**Please do not use these logos for any other purpose than Discord server 
logos.**

## Logos general design guidelines

Follow the logo for Finland in priority, as it is the first one that was made.

The general guidelines are:

* **The position and scaling of the EPITA logo must be left as is.**
  This is because the logos follow the same shape as the "official" Discord 
  school servers in terms of position and scaling.
* The flag of the country must be embedded in the logo, unless the flag really
  does not fit in nicely.
* The background must have a subtle gradient (bottom darker than top). The color
  must be either 
  * A darker or brighter version of the colors of the flag
  * A color that appears on the country's coat of arms
* Keep in mind that Discord server logos are circles that expand to rectangles
  with rounded corners when hovered over or selected.

## Repository notes

* Using Inkscape? Make sure you are using "Simple SVG" when saving to this
  repository, or else nasty metadata may be leaked (and the SVG will be much
  larger using Inkscape SVG anyway).
* The organization is as follows:
  ```
  <root>
  +- README.md
  +- <country code>
     +- logo_<country code>.svg
     +- logo_<country code>_<variant description>.svg
  ```

## TO-DO

The ultimate goal is to have one logo per destination, even if a Discord server
does not exist yet.

### Americas

- [ ] Bolivia `bo`
- [ ] Brazil `br`
- [ ] Canada `ca`
- [ ] Columbia `co`
- [ ] Mexico `mx`
- [ ] Peru `pe`
- [ ] USA `us`

### Asia

- [ ] Bahrain `bh`
- [ ] China `cn`
- [ ] Hong Kong `hk`
- [ ] India `in`
- [ ] Israel `il`
- [ ] Jordan `jo`
- [ ] South Korea `kr`
- [ ] Taiwan `tw`
- [ ] Thailand `th`
- [ ] United Arab Emirates `ae`
- [ ] Vietnam `vn`

### Europe

- [ ] Czech Republic `cz`
- [ ] Finland `fi`
- [ ] Hungary `hu`
- [ ] Ireland `ir`
- [ ] Italy `it`
- [ ] Latvia  `lv`
- [ ] Lithuania `lt`
- [ ] Poland `po`
- [ ] Spain `es`
- [ ] Turkey `tr`
- [ ] Ukrain `ua`
- [ ] United Kingdom `gb`

### Others

- [ ] South Africa
- [ ] Australia
- [ ] New Zealand
