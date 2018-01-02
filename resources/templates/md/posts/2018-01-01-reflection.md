{:title "Reflection of 2017"
 :layout :post
 :tags ["personal"]
 :toc true}

## Books Read

- [Implementing OpenShift][os1]
- [Load Balancing With HAProxy][hap]
- [Getting Started With OpenShift][os2]
- [Complete NGINX Cookbook][nginx]

## Places Travelled

### Seattle

I went to Seattle under unfortunate circumstances. Nonetheless,
it was a great trip. Seattle and the surrounding cities are
quite lovely and significantly less dense. Public transportation
is quite good. Awesome stores like Mox that don't have
equivalents in the Bay Area.

### San Diego

We went to San Diego twice this year. The first time was to witness
my sister's High School graduation. We stayed in a Tiny Home that
was actually quite nice. I would even consider living in a tiny
home permanently.

### San Juan Capistrano

### King's Canyon National Park

This year we went to camping at our traditional camping
grounds. Unfortunately, the trip was quite awful. The campgrounds
were excessively crowded and there were enough folks that were
quite disrespectful to not only other campers but nature herself.
It doesn't make a lot of sense to me why these people are
camping if they aren't there to enjoy nature. If you're looking
to have a good time you can do that somewhere else.

Besides that, the forests have taken quite a beating in recent
years. Most of the forests are burned down are starting to turn
red from bark beetle. This is due to the lack of enough water
for the trees to defend themselves. It's quite sad and campers
certainly don't help the situation. This was probably the last
time I'll go to King's Canyon. Not because I hate it or had a
bad experience, but because we need to let these forests
recover.

## First Year of DevOps

It's been an incredible journey transitioning from a Marketing
Engineer into DevOps.

Trying to leave out any specific projects I worked on at my
current company. Here is a list of tools I've had the chance
to work with (that I haven't worked with prior).

### Jenkins

I never spent a whole lot of time with Jenkins, but this year I
got the opportunity to work a ton with it. In all I think Jenkins
is a good tool. There are definitely some things Jenkins could
work on to improve, but for the current company I work for it
seems like a good fit.

### Ansible

I wrote some Playbooks/Roles for my current employer and for
myself this year. For my employer we decided to scrap what we
had and went with Chef/Terraform instead.

Ansible's syntax is wonky, but the setup is trivial. It's neat
how extensible the tool is and I definitely want to do more with
it. Personally though, I wouldn't put it in in the same category
as other tools like CFEngine, Puppet or Chef. I find that it's
better suited as a place to organize scripts that interact with
*centralized* services. Whereas I find tools like Puppet better
at converging *decentralized* machines.

### Chef

I didn't work a ton with Chef this year, but I also feel like I
understand Chef's weak points a lot more. This definitely makes
me want to understand Chef and Puppet more than I already do.

### Terraform

Not unlike my Chef experience, I haven't done a ton with
Terraform, but I feel like I understand it's weak points. I
view Terraform as a more simplified and less featured
version of Ansible. For now, it's a fine tool, but I worry
what happens to it once a single cluster gets excessively
large or if it becomes unmanageable once there are too many
clusters.

Like Ansible, it's neat that it's extensible via stdout and I
hope to write some plugins myself.

[os1]: https://www.packtpub.com/virtualization-and-cloud/implementing-openshift
[hap]: https://www.amazon.com/Load-Balancing-HAProxy-availability-infrastructure-ebook/dp/B01M5CAJ2L/ref=tmm_kin_swatch_0?_encoding=UTF8&qid=&sr=
[os2]: https://www.openshift.com/promotions/ebook.html
[nginx]: https://www.nginx.com/resources/library/complete-nginx-cookbook/
