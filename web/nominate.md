---
layout: content
stylesheet:
javascript:
 - lib/jquery.validate.min
 - nominate
class: page__nominate

title: Nominate
permalink: nominate/

hero:
  image: "003"

meta:
  keywords:
  description:
  author:

sitemap:
  lastmod: 2015-05-28
  priority: 0.7
  changefreq: weekly
  exclude:
---
To nominate your athlete, team or volunteer into this year’s awards, simply fill in their details below and state which award you wish to put them forward for, demonstrating in a maximum of 250 words why you think they should be a winner at the 2015 Birmingham Sports Awards.

If you are shortlisted as a finalist you shall be contacted during the week commencing August 24th. As a finalist you will receive 2 tickets to the awards ceremony which will be held on Thursday, September 17, at Aston Villa Football Club.

All entries are to be judged by an independent judging panel compiled by Trinity Mirror.

<h2>Nomination Form</h2>

<form action="{{ site.api }}/nominate/v2/" method="post" name="nomination" id="nominate" novalidate>

  <label for="nomineesname">Nominees Name<sup class="required" title="Required">*</sup>:</label>
  <input name="nomineesname" id="nomineesname" type="text" size="42" placeholder="eg, Nominees Name" required>

  <label for="nomineesemail">Nominees Email:</label>
  <input name="nomineesemail" id="nomineesemail" type="text" size="42" placeholder="eg, nominees.name@email.co.uk">

  <label for="nomineesphone">Nominees Phone Number:</label>
  <input name="nomineesphone" id="nomineesphone" type="text" size="42" placeholder="eg, 0121 123 4567">

  <label for="award">Award Category: </label>
  <select name="award" id="award" required>
      <option value="">Select an award below:</option>
    <option value="Lifetime Achievement Award">Lifetime Achievement Award</option>
    <option value="Professional Sportsman of the Year">Professional Sportsman of the Year (19 years and above)</option>
    <option value="Professional Sportswoman of the Year">Professional Sportswoman of the Year (19 years and above)</option>
    <option value="Professional Young Sportsperson of the Year">Professional Young Sportsperson of the Year (up to the age of 18)</option>
    <option value="Team of the Year">Team of the Year</option>
    <option value="Amateur Sportsman of the Year">Amateur Sportsman of the Year</option>
    <option value="Amateur Sportswoman of the Year">Amateur Sportswoman of the Year</option>
    <option value="Manager/Coach of the Year">Manager/Coach of the Year</option>
    <option value="Club of the Year">Club of the Year</option>
    <option value="Community Award">Community Award</option>
    <option value="Volunteer of the Year Award">Volunteer of the Year Award</option>
    <option value="Junior Team of the Year">Junior Team of the Year (11&ndash;19 years)</option>
    <option value="Junior Sportsperson of the Year">Junior Sportsperson of the Year (11&ndash;18 years)</option>
  </select>

  <label for="reason">I would like to nominate the nominee for this award because<sup class="required" title="Required">&#8224;</sup>:</label>
  <textarea name="reason" cols="33" rows="6" id="reason" placeholder="I would like to nominate the nominee for this award because..."></textarea>

  <label for="nominatorname">Your Name:<sup class="required" title="Required">*</sup></label>
  <input name="nominatorname" id="nominatorname" type="text" size="42" placeholder="eg, My Name" required>

  <label for="nominatoremail">Your Email:<sup class="required" title="Required">*</sup></label>
  <input name="nominatoremail" id="nominatoremail" type="text" size="42" placeholder="eg, my.name@email.co.uk" required>

  <label for="nominatorphone">Your Phone Number:</label>
  <input name="nominatorphone" id="nominatorphone" type="text" size="42" placeholder="eg, 0121 123 4567">

  <p><small><sup class="required">*</sup>Required. <sup class="required">&#8224;</sup>Maximum of 250 words.</small></p>


  <input name="submit" type="submit" class="btn btn--primary btn__large btn__half" id="submit" title="Submit" value="Submit Nomination">

</form>


Once you have completed the nomination form, you will be sent a welcome email.

All information provided by applicants to the Birmingham Sports Awards 2015 will be regarded as confidential and shared only between the publication Trinity Mirror, the organiser Champions (UK) plc and the judging panel.

All data will be securely stored and, following completion of the Birmingham Sports Awards 2015, all applications and associated information will be deleted by the Trinity Mirror and Champions (UK) plc. Contact information will be retained by the organisers for marketing purposes. Information will not be passed to third parties.
