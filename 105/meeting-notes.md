# SMART Meeting Notes, Wednesday 24th July 2019 

All slides available: https://trac.ietf.org/trac/ietf/meeting/attachment/wiki/105side-slides/ 

## Chairs Intro [slides](https://trac.ietf.org/trac/ietf/meeting/attachment/wiki/105side-slides/IETF%20105%20-%20SMART%20Chair%20Slides.pptx) 

The format of the meeting is: 

* History of SMART 

* Charter 

* Drafts 

* Next steps 

### History 

The area of attack defence is ripe for research right now.  
- At IETF 101, March 2018 - a gap in attack defence needs and considerations in the community was identified  
- At IETF 102, July 2018 - the idea of some work around attack defence was presented at saag and encouraged 
- At IETF 103, November 2018 - SMART held a planning meeting 
In February 2019, the [CARIS2](https://www.internetsociety.org/caris2) workshop was held in Boston 
- At IETF 104, we held an IAB-sponsored meeting (not-quite-a-BoF) with 150+ attendees, about half of the room interested in the work and keen to contribute 
- At IETF 105 – now! - having a side meeting for next steps. 

Kathleen: We’re seeing what work comes in and the researchers that are getting interested in this. We have to figure out new ways to do things and having cyber security functions fulfilled will aid in more widespread deployment of new encrypted protocols.  
Kirsty: it has been harder to attract academic research without being chartered as a group, hopefully this will change going forward. 

### Charter 

Discussion of the charter that was rejected ([link](https://github.com/smart-rg/drafts/commit/88a77ce140f6ed1f35dd27e30a6c9d31f370ade9#diff-d3f06a30df3bedb49ac54019c1f85d15)) 

Kirsty’s personal opinion is that the work just needs to be done; we don’t mind where. 
Perhaps one of the more contentious subjects was suggesting design considerations, using the word ‘inform’: in context, the British English means “make information available” but in American English this could mean “instruct”. It's the former and not the latter! One aim for example is to make available research that could form the basis of a potential future review of 3552. 
 

Question: Current drafts seem to be focussing on endpoint security, are protocols also in scope? What’s the aspiration – is it specifically on endpoint trust and security? A: The drafts that came in start with endpoint security, because we need to work from a bootstrapping baseline. We’ll move to a fuller security picture.  

Q: OAuth had workshops following the publication of the main document. Can we replicate what’s happened with OAuth across all the protocols? Not sure whether this would scale to all working groups by channelling it through a single RG.  A: Unlike these workshops, we won’t be pushing back changes. 

Q: Is the group only about malware? A: no, SMART is a backronym, this is about all malicious attacks. 

Q: A lot of the work we are doing around TLS measurement and malware wouldn’t result in any changes to the TLS base protocol, it would be just informational, right? A: Right. 

Comment: If you want to influence protocols, that needs to go into the IETF. Someone raises that CFRG does influence the IETF and that’s an IRTF group.

Colin (IRTF Chair): CFRG is different because it’s doing research on crypt. Not pushing things into IETF  

A: SMART could have been like that model, but we've been told not to look at CFRG as a model. 

Colin: The SMART charter was written in a way that focussed on engineering efforts. It’s about finding an appropriate home for the work. 

Kathleen: wouldn’t rule out research, the area is ripe for research.  
 

### Drafts 

Now we talk about the drafts. 

## CLESS [slides](https://trac.ietf.org/trac/ietf/meeting/attachment/wiki/105side-slides/CLESS-UPDATE-SMART.pptx) 

Capabilities and Limitations of Endpoint Security Solutions: [CLESS](https://datatracker.ietf.org/doc/draft-taddei-smart-cless-introduction/), presented by Arnaud Taddei, Symantec. 

What would be the model of endpoint security in an ideal world? Open call in June, 25 registered, decided to detach endpoint model. This draft got some press coverage in the German press and calls by U.S. journalists. Deutsche Bank and Schindler also interested in the work.  
Most concerned about co-ordination – a lot of effort required here – he doesn’t want the scope to grow and there is pressure for the scope to creep. Also a note that some of the work is going to be really hard – there is talk about starting a section on economics – this is going to be hard to write. Some basic collaboration issues to be resolved. Side meeting Thursday 4pm in the Coller room. 

 

## Endpoint taxonomy for CLESS [slides](https://trac.ietf.org/trac/ietf/meeting/attachment/wiki/105side-slides/IETF%20105%20-%20Slides%20for%20CLESS%20Endpoint%20Taxonomy.pptx) 

Presented by Mark McFadden: [draft-mcfadden-smart-endpoint-taxonomy-for-cless](https://datatracker.ietf.org/doc/draft-mcfadden-smart-endpoint-taxonomy-for-cless/) 

There’s a description of what the endpoints look like at the start of the CLESS draft. 
There has been a limited amount of research in this, NIST has done some, need more research and community consultation. There are diverse devices you might talk about; there are seven groups of devices in this draft (not too many, not too few). Provides descriptions of groups and their characteristics. Intent is to provide a foundation for the CLESS draft. This is a missing element in security conversations anyway, so this is a taxonomy that could be used in other settings as well. 
 
Kathleen: Attackers have shifted their techniques such that some IOCs are not useful – hashes are not sufficient. Detection of threats is going to require new techniques and this is an important area of research. 
 
## RFC 3552 Research Methodology [slides](https://trac.ietf.org/trac/ietf/meeting/attachment/wiki/105side-slides/IETF%20105%20-%20Slides%20for%20RFC%203552%20Research%20Methodology.pptx) 

[draft-mcfadden-smart-rfc3552-research-methodology](https://datatracker.ietf.org/doc/draft-mcfadden-smart-rfc3552-research-methodology/), presented by Mark McFadden. 
 
There is a need to update Internet Threat Model – but this is a significant piece of work. There are some drafts (Arkko, Farrell, [Lazanski](https://datatracker.ietf.org/doc/draft-lazanski-smart-users-internet/)) that provide a starting point. Mark proposes a piece of research to inform (in the British sense of the word!) the discussions – if you want to learn how successful Security Considerations are currently, look at what you’ve done in the past. OAuth sec cons talks about threats and mitigations. Others are very limited. He proposes a review of what sec cons are like over the last n  years. Add this to the discussion about how we might revise RFC 3552. Both quantitative and qualitative analysis. This draft is about how to do that review. Mark has looked at 250 RFCs and is now looking for comments on the methodology. Mark would contribute to the resulting research work that used this methodology. 

Q: How many people could contribute to the work? A: Mark thinks 5 or 6 would be best. 
 

## An Internet For Users Again [slides](https://trac.ietf.org/trac/ietf/meeting/attachment/wiki/105side-slides/IETF%20105%20-%20New%20Internet%20Threat%20Model%20Lazanski.pptx) 

Dominique Lazanski presents: [draft-lazanski-smart-users-internet](https://datatracker.ietf.org/doc/draft-lazanski-smart-users-internet/) 

Introduces a new threat model, with a focus on endpoint security, data breaches and attacks we see today. Not comprehensive and not meant to be, but meant to start discussion. This should be discussed in conjunction with other drafts on threat models. Thanks for all the feedback so far. 

Comment: read the draft, had some issues, worried that the prose is a bit inflammatory.

Kathleen: Yes, that came through on the list, it will be edited. 

Comment: Seems to be a perception that RFC3552 prohibits work that is not ComSec-y. Is that what you’re saying? Can you point to something specific? 

Kirsty: there’s a section in RFC3552 that says once the endpoint is compromised, there’s nothing you can do - game over. This ignores large parts of attack defence - “defend” is an overloaded word, but there are opportunities to detect infection and prevent further harm, and for mitigation after. This section does not consider lateral movement around the network or a full attack chain. 

Kathleen: people who are less aware may just read RFC3552 and take it as their basis for the security considerations. It’s just an evolution of a proposal to give more information to people who are less aware, citing Lockheed-Martin's cyber kill chain. 
 
## Supporting Secure User Interaction [slides](https://trac.ietf.org/trac/ietf/meeting/attachment/wiki/105side-slides/IETF%20105%20-%20SMART%20draft-sasse-smart-secui-question.pptx) 
Presented by Kirsty P., [draft-sasse-smart-secui-questions](https://github.com/smart-rg/drafts/blob/master/draft-sasse-smart-secui-questions.txt) 

This draft describes open questions in supporting usable security at UI level. There is evidence from usable security research that people just click through warnings, that we overburden users and more. There are four open questions in the document around: vocabulary, usable security basics, role of trust signalling, and UI indicators. 
Comment: These are the kind of research questions that belong in a research group. This is about exploring the limits to security.  
Comment: identified that this is the most difficult problem to fix. There’s a problem that we keep forgetting user security and the human. There is no research and it’s a very hard problem – this is completely valid work. 
Comment: Also thinks this is really important, not thought about enough - how do I know I’m using DNSSEC or ESNI?  
Comment: some of this came up in the ADD BOF yesterday. 

Comment: Wants to continue this discussion – I don’t know whether it would be useful for end-users to know everything, because at some point it just becomes meaningless noise. Would be useful to detangle that and understand the responsibility of protocols to just do it right and in the best interests for a user. Power-users like us would be able to discover whether DNSSEC is being used – but this is off-loading decision making onto users. Demarcate where the responsibility lies. Kirsty: this is one of the questions (what is a manageable set of tasks for a user?) being thought about in the draft already.  
Comment: The UI is just the surface of the UX – we don’t even know whether we should expose these signals. There is no research, no theory here.  
Comment: Some countries have regulatory bodies that can put in place security practices such as DNSSEC. No such regulation in Canada. Companies not incentivised to provide discriminators. 

Kathleen: open the floor – is anyone else working on research they’d like to share?  

Mallory, Article 19: is doing research that looks at spam filtering done by the biggest three providers of e-mail. Where could this land? Q: is this from a technical point of view? A: Yes, and wider. Legitimate e-mailers who are on blocklists being told to work around the AI spam filters. 

Blake, Cisco: Also has research: most of his current work is around misuse of privacy enhancing technologies. Could be on IPv6 and different types of proxies. Doing a lot of measurement studies – for example, cipher suite randomisation was open sourced in 2018, two months later malware was using this. 
 
# Going forward 

## For the six drafts 

CLESS has a side meeting on Thursday. All feedback on other drafts is welcome, on the list or direct to the author(s).

## For the group/charter 
Chairs will happily take feedback on the charter and potential ways forward. In Chairs and many others’ view, it’s more important that the work gets done rather than structuring. We can look at research or engineering, whichever fits. Open question: what’s the future in this community? 
 
Dave Plonka (MAPRG chair): Might want to look at the MAPRG charter for inspiration; MAPRG currently has security-related talks that would fit better with SMART and MAPRG always has a full agenda, so it could afford to split this work out to SMART. SMART is welcome to bring measurement stuff to MAPRG in the meantime. 
 
And that wraps up the meeting. Stay tuned for our next steps. 

 

 
