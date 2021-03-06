# PeeringDB

## Getting help

* Please log bugs and feature requests at [GitHub](https://github.com/peeringdb/peeringdb/issues).

* Several PeeringDB mailing lists are listed below.

* Questions, comments and everything else should go to <support@peeringdb.com>.

## Mailing lists

We have changed the way in which PeeringDB will be announcing future enhancements, changes, maintenance windows, and other information. If you would like to be notified of certain events, or participate in certain discussions, please subscribe to one of the following email lists:

* [PeeringDB Announce](http://lists.peeringdb.com/cgi-bin/mailman/listinfo/pdb-announce)
    All PeeringDB administrative information, such as upgrades,
    maintenances, outages, etc.

* [PeeringDB Governance](http://lists.peeringdb.com/cgi-bin/mailman/listinfo/pdb-gov)
    Discussion list for PeeringDB governance issues This is a
    community-based effort, the community’s input will help guide the
    future of the PeeringDB (as it has always done).

* [PeeringDB Technical](http://lists.peeringdb.com/cgi-bin/mailman/listinfo/pdb-tech)
    Discussion of the back end of PeeringDB & other technical topics

* [PeeringDB User-Discuss](http://lists.peeringdb.com/cgi-bin/mailman/listinfo/user-discuss)
    All other list traffic.

Our goal is to give you all the information you want, and no more.  Please subscribe to any of these lists you feel are appropriate, or none. You will still be able to use the database even if you are not subscribed to any lists.

## Quick start

PeeringDB is available at <https://www.peeringdb.com/> with self-describing API docs at <https://www.peeringdb.com/apidocs/>.  More thorough docs are at [API Specs](api_specs.md), but in a nutshell, just prepend the URL with `api/` to get that object in JSON.

For example:
<https://www.peeringdb.com/net/1>
becomes:
<https://www.peeringdb.com/api/net/1>

List all via API by taking the `id` off:
<https://www.peeringdb.com/api/net>

Local database replication is accomplished with this [command line tool](https://github.com/peeringdb/peeringdb-py), please see the [documentation](http://peeringdb.github.io/peeringdb-py/cli/#sync) for more information.

## Guides

- [es] [Guía corta para uso de peeringdb.com](guide/guia_PeeringDB.pdf) - Fabián Mejía
- [pt-BR] [Guia de cadastro de informações de Facilities no PeeringDB](guide/PeeringDB_Cadastro_de_Facilities.pdf) - Julimar Lunguinho Mendes / Equipe de Engenharia

## Presentations

#### 2018

- [PeeringDB Frontend Translation Project](presentation/20180907_apnic46_peeringdb_i18n_mawatari.pdf) at [APNIC 46](https://conference.apnic.net/46/), Noumea, NC - September 12, 2018 - Masataka Mawatari
- [PeeringDB Update](presentation/20180821-AfPIF2018-Nipper.pdf) at [AfPIF2018](https://www.afpif.org/afpif2018/), Cape Town, ZA - August 23, 2018 - Arnold Nipper
- [PeeringDB for IXes](presentation/20180820-AF-IX@AfPIF2018-Nipper.pdf) at [AFIX](https://www.af-ix.net/), Cape Town, ZA - August 20, 2018 - Arnold Nipper
- [Introduction to PeeringDB API](presentation/20180810-SANOG32-Lightning-Introduction-to-PeeringDB-API-Nipper.pdf) at [SANOG 32](http://www.sanog.org/sanog32/), Dhaka, BD - August 10, 2018 - Arnold Nipper
- [PeeringDB Update](presentation/20180809-SANOG32-Update-Nipper.pdf) at [SANOG 32](http://www.sanog.org/sanog32/), Dhaka, BD - August 9, 2018 - Arnold Nipper
- [PeeringDB: What is it, how to and benefits](presentation/20180622-NEPF-Gilmore.pdf) at [New England Peering Forum 2018](http://nepeeringforum.org/), Cambridge, MA, US - June 22, 2018 - Patrick W. Gilmore
- [PeeringDB Update](presentation/20180619-SEE7-Lightning-Nipper.pdf) at [SEE 7](https://www.ripe.net/participate/meetings/regional-meetings/see/see-7), Timișoara, R0 - June 18, 2018 - Arnold Nipper
- [PeeringDB Update](presentation/20180605-ENOG15-Nipper-V2.pdf) at [ENOG 15](https://www.enog.org/enog-15/programme/agenda/), Moscow, RU - June 5, 2018 - Arnold Nipper
- [PeeringDB Update](presentation/20180524-SwiNOG-33-Lightning-Nipper-V2.pdf) at [SwiNOG 33](http://www.swinog.ch/meetings/swinog33/index.asp), Berne, CH - May 24, 2018 - Arnold Nipper
- [PeeringDB Update e cadastro de Facilities](presentation/gter45-peeringdb.20180515.pdf) at [GTER 45](http://gtergts.nic.br/), Florianópolis, BR - May 22, 2018 - Julimar Lunguinho Mendes ([video](https://www.youtube.com/watch?v=W0hSdRr4UW0) start 1:08:29 and finish 1:20:14)
- [PeeringDB Update](presentation/20180516-RIPE76-Lightning-Nipper-V2.pdf) at [RIPE 76 Connet Working Group](https://ripe76.ripe.net/programme/meeting-plan/connect-wg/), Marseille, FR - May 16, 2018 - Arnold Nipper ([video](https://ripe76.ripe.net/archives/video/49))
- [PeeringDB Update](presentation/20180508-AIS2018-Nipper-v2.pdf) at [African Internet Summit 2018](https://internetsummitafrica.org/), Dakar, SN - May 8, 2018 - Arnold Nipper
- [PeeringDB Update](presentation/20180309-DKNOG8-Lightning-Nipper.pdf) at [DKNOG8](https://dknog8.dknog.dk/), Copenhagen, DK - March 9, 2018 - Arnold Nipper
- [PeeringDB Update](presentation/20180307-CEE-Peering-Days-Lightning-Nipper.pdf) at [CEE Peering Days 2018](https://www.peeringdays.eu/programme.php), Berlin, DE - March 7, 2018 - Arnold Nipper
- [Introduction to PeeringDB](presentation/20180226-Apricot2018-Nipper.pdf) at [APRICOT 2018](https://2018.apricot.net/program/schedule/#/day/8/peering-and-interconnection-ii-global), Kathmandu, NP - February 26, 2018 - Arnold Nipper
- [PeeringDB Update](presentation/20180224-17th-APIX-Nipper.pdf) at [APIX Meeting #17](http://apix.asia/?page_id=75), Kathmandu, NP - February 24, 2018 - Arnold Nipper
- [PeeringDB Introduction](presentation/20180208-Capacity-India-and-SAARC-Nipper.pdf) at [Capacity India & SAARC 2018](http://www.capacityconferences.com/India-Connect-Agenda), New Delhi, IN - February 8, 2018 - Arnold Nipper

#### 2017

- [PeeringDB Update](presentation/20171114-alnof-sanghani.pdf) at [NIX.cz Member Meering](https://www.nix.cz/), Prague, CZ - November 23, 2017 - Bijal Sanghani
- [PeeringDB Update](presentation/20171123-DENOG9-nipper.pdf) at [DENOG9](http://www.denog.de/de/meetings/denog9/agenda.html), Darmstadt, DE - November 23, 2017 - Arnold Nipper
- [PeeringDB Update](presentation/20171114-alnof-sanghani.pdf) at [ALNOF](https://alnof.namex.it/), Tirana, AL - November 14, 2017 - Bijal Sanghani
- [PeeringDB Update](presentation/20171101-Peering-Asia-nipper.pdf) at [Peering Asia 1.0](http://peeringasia.com/), Kyoto, JP - November 1, 2017 - Arnold Nipper
- [PeeringDB Update](presentation/20170926-topix-meeting-sanghani.pdf) at [TOP-IX Meeting](https://www.top-ix.org/en/2017/07/31/104342/), Torino, IT - September 26, 2017 - Bijal Sanghani
- [PeeringDB Update](presentation/20170915-Neutral-Peering-Day-2017-nipper.pdf) at [NPD 17](https://neutralpeeringdays.net/#Program), The Hague, NL - September 15, 2017 - Arnold Nipper
- [PeeringDB Update](presentation/20170906-SAFNOG-3-nipper.pdf) at [SAFNOG-3](http://www.safnog.org/safnog-3-with-iweek-in-durban), Durban, ZA - September 6, 2017 - Arnold Nipper
- [PeeringDB Update](presentation/20170824-AfPIF2017-nipper.pdf) at [AfPIF 2017](http://www.internetsociety.org/afpif/2017/), Abidjan, CI - August 24, 2017 - Arnold Nipper
- [PeeringDB Update](presentation/20170710-SANOG30-nipper.pdf) at [SANOG 30](http://www.sanog.org/sanog30/program.html) Peering Forum, Gurgaon, IN - July 10, 2017 - Arnold Nipper
- [More benefits from PeeringDB](presentation/20170622-decix-technical-meeting-nipper-v2.pdf) at [DE-CIX Technical Meeting](https://www.de-cix.net/en/news-events/events/de-cix-technical-meeting), Frankfurt, DE - June 22, 2017 - Arnold Nipper
- [PeeringDB Update](presentation/20170605-nanog-70-hughes-peeringdb.pdf) at [NANOG 70](https://www.nanog.org/meetings/nanog70/home), Bellevue, WA, US - June 5, 2017 - Aaron Hughes
- [PeeringDB Update](presentation/20170602-bosnog-mcmanus.pdf) at [BOSNOG Meeting & IX Peering Forum](https://www.meetup.com/BOSNOG-The-Boston-Network-Operators-Group/events/239045101/), Cambridge, MA, US - June 2, 2017 - Stephen McManus
- [Orientações no preenchimento de participantes do IX.br](presentation/gter43-peeringdb.20170522.pdf) at [GTER 43](http://gtergts.nic.br/), Foz do Iguaçu, BR - May 25, 2017 - Julimar Lunguinho Mendes
- [PeeringDB Update](presentation/20170523-ENOG13-Nipper.pdf) at [ENOG 13.0](https://www.enog.org/enog-13/), Saint Petersburg, RU - May 23, 2017 - Arnold Nipper
- [PeeringDB Update](presentation/20170426-gpf-12.0-hughes-peeringdb.pdf) at [Global Peering Forum 12.0](https://www.peeringforum.com/gpf-12-0-peeringdb-update/), New York, NY, US - April 26, 2017 - Aaron Huges
- [PeeringDB](presentation/20170406-ESNOG19-Nipper.pdf) at [GORE/ESNOG Reunion 19](http://www.esnog.net/2017/01/goreesnog-reunion-19-csuccatnix-barcelona/), Barcelona, ES - April 6, 2017 - Arnold Nipper
- [PeeringDB](presentation/20170323-CEE-Peeringdays-Nipper.pdf) at [CEE Peering Days 2017](http://www.peeringdays.eu/), Ljubljana, SL - March 23, 2017 - Arnold Nipper
- [PeeringDB 2.0](presentation/20170228-Apricot2017-Nipper.pdf) at [APRICOT 2017](https://2017.apricot.net/), Ho Chi Minh City, VN - February 28, 2017 - Arnold Nipper

#### 2016

- [PeeringDB](presentation/2016-11-23-kikeautumn16-2.pdf) at [19 KIKE Conference](http://kikeevents.com/en/category/19-kike-conference/), Serock, PL - November 23, 2016 - Robert Jakub
- [PeeringDB 2.0](presentation/20161103-ITNOG2-Nipper-peeringdb.pdf) at [ITNOG2](http://www.itnog.it/itnog2/), Bologna, IT - November 3, 2016 - Arnold Nipper
- [PeeringDB Product Committee Charter Survey](presentation/20160919-epf11-Loos-peeringdb.pdf) at [EPF 11](https://www.peering-forum.eu/), Sofia, BG - September 20, 2016 - Eric Loos
- [PeeringDB 2.0](presentation/20160916-npd16-Wollny-peeringdb.pdf) at [NPD 16](http://www.neutralpeeringdays.net/), The Hague, NL - September 16, 2016 - Walt Wollny
- [PeeringDB 2.0](presentation/2016-08-30_afpif2016-Nipper-peeringdb.pdf) at [AfPIF 2016](https://www.internetsociety.org/afpif-2016/), Dar es Salaam, TZ - August 30, 2016 - Arnold Nipper
- [PeeringDB 2.0 for IXPs](presentation/2016-08-29_afix2016-Nipper-peeringdb.pdf) at [AFIX 2016](http://www.af-ix.net/?q=resources/2016/08/afix-2016-meeting-agenda), Dar es Salaam, TZ - August 29, 2016 - Arnold Nipper
- [PeeringDB 2.0](presentation/2016-06-07_PeeringDB-2.0_ENOG11.pdf) at [ENOG 11](https://www.enog.org/meetings/enog-11/), Moscow, RU - June 7, 2016 - Arnold Nipper
- [PeeringDB 2.0](presentation/2016-05-25_81-ripe-72-peeringdb.pdf) at [RIPE 72](https://ripe72.ripe.net/), Copenhagen, DK - May 25, 2016 - Greg Hankins
- [PeeringDB 2.0](presentation/2016-05-12_chi-nog-06-peeringdb.pdf) at [CHI-NOG 06](http://chinog.org/meetings/chi-nog-06/), Chicago, IL, US - May 12, 2016 - Matt Griswold
- [PeeringDB 2.0 e o Cenário Brasileiro](presentation/2016-05-12_PeeringDB-2.0_GTER_41.pdf) and [IX.br Guia de cadastro de informações de ASNs no PeeringDB](presentation/2016-05-12_IX.br_PeeringDB_Guide.pdf) at [GTER 41](http://gtergts.nic.br/), Uberlândia, BR - May 12, 2016 - Eduardo Ascenço Reis
- [PeeringDB 2.0 for IXPs](presentation/2016-04-26_PeeringDB_28th_Euro-IX_Forum.pdf) at [28th Euro-IX Forum](https://www.euro-ix.net/), Luxembourg, LU - April 26, 2016 - Greg Hankins / Arnold Nipper
- [RIPE SEE 5](https://www.ripe.net/participate/meetings/regional-meetings/see-5), Tirana, AL - April 19, 2016 - Arnold Nipper
- [PeeringDB 2.0](presentation/2016-04-21_PeeringDB_UKNOF34.pdf) at [UKNOF34](https://indico.uknof.org.uk/conferenceDisplay.py?confId=36), Manchester, UK - April 21, 2016 - Greg Hankins
- [PeeringDB Update](presentation/2016-04-13_PeeringTrack-PDB-Update-GPF11.pdf) at [GPF 11](https://www.peeringforum.com/), Los Angeles, CA, US - April 13, 2016 - Aaron Hughes
- [NetNod](http://www.netnod.se/netnod-spring-meeting-2016), Stockholm, SE - March 17, 2016 - Job Snijders
- [DKNOG6](http://www.dknog.dk/events/dknog6/), Copenhagen, DK - March 10, 2016 - Job Snijders
- [PeeringDB Update](presentation/PeeringTrack-PDB-Update-20160205.pdf) - Aaron Hughes
    - [APRICOT 2016](https://2016.apricot.net/), Auckland, NZ - February 23, 2016 - Aaron Hughes
    - [NANOG 66](http://nanog.org/meetings/nanog66/home), San Diego, CA, US - February 10, 2016 - Aaron Hughes
- [PeeringDB Version 2 Coding Introduction](presentation/PeeringDB_Version_2-Coding_Introduction.pdf) at [NANOG 66](http://nanog.org/meetings/nanog66/home), San Diego, CA, US - February 8, 2016 - Matt Griswold

#### 2015

- [PeeringDB Version 2 Brazil](presentation/PeeringDB_Version_2-Brazil.pdf) - Matt Griswold / Greg Hankins
    - [IX (PTT) Fórum 9](http://ix.br/pttforum/9/index-en.html), São Paulo, BR - December 8, 2015 - Greg Hankins
- [PeeringDB Version 2 Introduction](presentation/PeeringDB_Version_2-Introduction.pdf) - Matt Griswold
    - [27th Euro-IX Forum](https://www.euro-ix.net/news-and-events/euro-ix-forum/), Berlin, DE - October 26, 2015 - Greg Hankins
    - [DENOG7](http://www.denog.de/meetings/denog7/?lang=en), Darmstadt, DE - October 30, 2015 - Arnold Nipper 

## Tools

This section lists tools for using PeeringDB, and tools that use PeeringDB.

* [django-peeringdb](http://peeringdb.github.io/django-peeringdb/) is a Django library with a local PeeringDB database sync.  It defines the database schema to create a local database copy.  The library is easy to integrate into a common framework for local tools and custom interfaces, and also supports multiple database engines (MySQL, Postgres, SQLite).

* The [Isolario project](https://www.isolario.it/index.php) improve knowledge about the AS-level ecosystem of the Internet by increasing the amount of Autonomous Systems (ASes) from which BGP data is collected. Isolario offers network operators services based on the real-time analysis of inter-domain routing from different points of view in return for full routing tables.

* [Ixgen](https://github.com/ipcjk/ixgen/blob/master/Readme.md) is yet another open source, multiplatform peering configuration generator that is based on the PeeringDB API.  It can also run its own server for faster results.  Ixgen is configured using an INI- or JSON-style format, and produces custom template-driven or fixed JSON-style configurations,

* [peeringdb-py](http://peeringdb.github.io/peeringdb-py/) is a Python client for PeeringDB.  It features functions to get objects and display them in JSON or YAML format, and provides a whois-like display of records.  The client also has an integrated local database sync, and provides a Python library for integration with custom tools.  [Some examples](https://github.com/grizz/pdb-examples) are available too.

* [Pinder](http://github.com/dotwaffle/pinder) is a tool that facilitates peering.  If peering is desired between two networks, and you're happy to just configure sessions without a commercial agreement, Pinder acts as the middle man.  You can submit the request via either a basic web UI or an API, and the other network is notified or can periodically check their outstanding requests.  If both network agree to peer, they are notified to configure a session.  Once both networks indicate that sessions are configured and established, the request is then deleted. [A brief slide deck](http://accel.waffle.sexy/pinder.pdf) explains the functionality in more detail.

* [TraceMON](https://labs.ripe.net/Members/massimo_candela/tracemon-traceroute-visualisation-network-debugging-tool) is a tool for visualizing a network topology generated by traceroutes that provides one-click access to IXP and network information.  It also displays PeeringDB information and allows the user to update their record.  RIPE Atlas users can access it by selecting a [traceroute measurement](https://atlas.ripe.net/measurements/?search=&status=&af=&kind=2%2C4&age=#!tab-public) and clicking on the TraceMON tab.

## Open Source

#### Source code audit

PeeringDB commissioned a full audit of PeeringDB's source code in 2018. [Computest](https://www.computest.nl/) (the auditor) prepared a __Third Pary Memo__, this memo provides a high level overview of the outcome of the source code audit. The report is available [here](gov/misc/2018-05-16_Computest_Source_Code_Audit_TPM.pdf).

## Beta development

* The [PeeringDB beta server](https://beta.peeringdb.com/) is running the latest beta software version, with full access over HTTP and the API.  Note that changes made to the beta database are local to the beta server only, and are not reflected on the production servers.

* The [latest changes to PeeringDB](https://beta.peeringdb.com/changes) automagically redirects to the list of issues on PeeringDB's GitHub repository that document all of the changes in the current beta version.


## Thank you!

### Translators

#### pt

- Robert Philips (NTT Communications)
- Ligio Gomes (NTT Communications)


## Historical data

* The PeeringDB 1.0 MySQL interface is gone.  The last available MySQL dump is archived at <https://www.peeringdb.com/v1/final_export.sql>.
* MySQL dumps from July, 29 2010 to March 14, 2016 are archived by CAIDA at <http://data.caida.org/datasets/peeringdb-v1/>.

## How you can help

* Check your entries and make sure everything looks correct

* Port any scripts to the new API

* Send us feedback

* Improve these docs

* Add or improve a [translation](translation/)

Thanks for your feedback, we look forward to hearing from you!
