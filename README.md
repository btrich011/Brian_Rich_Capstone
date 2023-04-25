<table>
<thead>
<tr>
<th align="center">Drop Data</th>
<th align="center">Plots</th>
<th align="center"></th>
<th align="center">Kmeans Model</th>
</tr>
</thead>
<tbody>
<tr>
<td align="center"><a href="https://github.com/btrich011/Brian_Rich_Capstone/blob/main/tick_drop1.csv">Drop CSV</a></td>
<td align="center"><a href="https://github.com/btrich011/Brian_Rich_Capstone/blob/main/plots.png">Exploratory Plots</a></td>
<td align="center"><a href="https://github.com/btrich011/Brian_Rich_Capstone/blob/main/Brian_Rich_Capstone5.ipynb">Model</a></td>
<td align="center"></td>
</tr>
</tbody>
</table>
<h1 dir="auto"><a id="user-content-history" class="anchor" aria-hidden="true" href="#history"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a>History</h1>
<p dir="auto">Ticks are important ectoparasites that pose a significant threat to both livestock
=======
# Introduction
This repository is my capstone project in the data science course OEAS895 —"Exploration of Machine Learning for the Analysis of Generational
Tick Colony Variability" 

## Table of contents
|Drop Data|                                                                             Plots                                                                              |                                                                                                                                              |                                                                               Kmeans Model                                                                                |
|:-----------------:|:---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------------------------------------------------:|:------------------------------------------------------------------------------------------------------------------------------------------------------------------:|
|[Drop CSV](https://github.com/btrich011/Brian_Rich_Capstone/blob/main/tick_drop1.csv)|              [Exploratory Plots](https://github.com/btrich011/Brian_Rich_Capstone/blob/main/plots.png)               |  [Model](https://github.com/btrich011/Brian_Rich_Capstone/blob/main/Brian_Rich_Capstone5.ipynb)                                         


# History
 
Ticks are important ectoparasites that pose a significant threat to both livestock
>>>>>>> 1201491bbcfc8165d97bc61ac1e5a1eed7216335
sustainability through damage to animals and human health due to the large number of pathogens
they may vector to their hosts (Levin and Schumacher, 2016). Ticks have a four stage life cycle
where after emerging from the egg the larvae, nymphs, and adults are obligate blood feeders that
remain attached to their hosts for several days in order to obtain the nourishment they require to
molt to the next stage of their development. Upon molting into adults the female ticks will feed
and produce eggs as they are mated by males. Female ticks will then feed until completely
engorged before dropping from their host (tick drop) to crawl away into the environment to lay
their eggs in a suitable place (Needham and Teel, 1991). Study of ticks in the wild is difficult at
best due to the factors involved in access to the hosts they prefer for the long periods of time in
which they remain attached. This is also a limiting factor in the collection of ticks for the
purposes of research in that sufficient numbers of specific strains may be difficult to obtain from
the wild.
Studies involving new tick management techniques necessitate access to large numbers of
ticks that are both free of pathogens and with similar genetic dispositions. Rearing methods like
those employed by Soneneshine, et al. (1999) can be used to safely rear many generations of
ticks in a laboratory setting and satisfy researchers needs. In many settings, dozens of
generations of a single strain may be reared without the need to add in additional genetic
diversity.
It has been theorized that long term inbreeding of colony ticks results in successive
generations speeding up their life cycle and needing to spend less time on the host before molting
and breeding. Those colony ticks may then no longer be representative of tick cohorts in the
wild, degrading their usefulness. By looking at the characteristics during tick drop over
successive generations we may see some of the variations caused by such inbreeding.
An analysis of tick drop data over the course of many generations through machine
learning may permit the prediction of when those colonies vary too far away from their base
strain to be useful. Analysis and model creation for ticks to simulate spread and life cycle have
been explored (Wang et al., 2017) but availability of tick drop data for analysis has not. This
presents an opportunity to progress our understanding by predicting the speed of each successive
generation to aid in researchers collection of gravid females at the time of drop and suggest when
a tick colony is too far “out of spec”. This would be useful in determining when to look at the
genetics of those colonies in order to see how far genetic drift has actually taken them when
compared the the initial colony characteristics.
We will use 40 generations of tick drop data for a single strain of Rhipicephalus
(Boophilus) microplus to train a supervised machine learning algorithm and then test its
predictive abilities to illustrate generational variability in mean drop time over a further 20
generations. Then we will compare the results of the ML predictions to the true generation result
gathered by research personnel during colony maintenance to determine if those predictions are
accurate. Target variables will include temperature as higher temperatures speed up the tick life
cycle, speed of female drop (i.e. the time period from the first female dropping from the host
until the last), the total number of dropped females per generation, the speed of life cycle
completion (time between larval infestation and female drop), and the average weight of the
<<<<<<< HEAD
females per generation.</p>
<p dir="auto">References
Levin, M. L., &amp; Schumacher, L. B. (2016). Manual for maintenance of multi-host ixodid ticks in the laboratory.
Experimental and Applied Acarology, 70(3), 343–367. <a href="https://doi.org/10.1007/s10493-016-0084-8" rel="nofollow">https://doi.org/10.1007/s10493-016-0084-8</a>
Maramorosch, K., Mahmood, F. E., &amp; Sonenshine, D. E. (1999). Maintenance of Ticks in the Laboratory. In
Maintenance of human, animal, and plant pathogen vectors. essay, Science Publishers.
Needham, G. R., &amp; Teel, P. D. (1991). Off-host physiological ecology of ixodid ticks. Annual Review of
Entomology, 36(1), 659–681. <a href="https://doi.org/10.1146/annurev.en.36.010191.003303" rel="nofollow">https://doi.org/10.1146/annurev.en.36.010191.003303</a>
Wang, H.-H., Corson, M. S., Grant, W. E., &amp; Teel, P. D. (2017). Quantitative models of rhipicephalus (boophilus)
ticks: Historical Review and synthesis. Ecosphere, 8(9). <a href="https://doi.org/10.1002/ecs2.1942" rel="nofollow">https://doi.org/10.1002/ecs2.1942</a></p>
<h1 dir="auto"><a id="user-content-objective" class="anchor" aria-hidden="true" href="#objective"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a>Objective</h1>
<p dir="auto">Use an unsupervised machine learning method to analyze 63 generations of tick drop data from colony raised "Rhipicephalus (Boophilus) microplus".  Kmeans will be utilized here for the initial analysis.</p>
<h3 dir="auto"><a id="user-content-dataset" class="anchor" aria-hidden="true" href="#dataset"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a>Dataset</h3>
<p dir="auto">Tick drop data was obtained from USDA ARS' Cattle Fever Research Laboratory in Edinburg, TX.</p>
<h3 dir="auto"><a id="user-content-python-version-and-packages" class="anchor" aria-hidden="true" href="#python-version-and-packages"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a>Python version and packages</h3>
<ul dir="auto">
<li>Python version 3.10.9</li>
<li>All the packages/versions used for this project can be found in <a href="https://github.com/btrich011/Brian_Rich_Capstone/blob/main/requirements.txt">Requirements</a> file.</li>
</ul>
</article>
  </div>

    </div>

  </readme-toc>

  

  <details class="details-reset details-overlay details-overlay-dark" id="jumpto-line-details-dialog">
    <summary data-hotkey="l" aria-label="Jump to line"></summary>
    <details-dialog class="Box Box--overlay d-flex flex-column anim-fade-in fast linejump overflow-hidden" aria-label="Jump to line">
      <!-- '"` --><!-- </textarea></xmp> --></option></form><form class="js-jump-to-line-form Box-body d-flex" data-turbo="false" action="" accept-charset="UTF-8" method="get">
        <input class="form-control flex-auto mr-3 linejump-input js-jump-to-line-field" type="text" placeholder="Jump to line&hellip;" aria-label="Jump to line" autofocus>
          <button data-close-dialog="" type="submit" data-view-component="true" class="btn">    Go
</button>
</form>    </details-dialog>
  </details>



    <div class="pt-3" >
      <details class="details-reset details-overlay details-overlay-dark " >
                <summary data-view-component="true" class="btn-link">    Give feedback
</summary>

  <details-dialog
    class="Box d-flex flex-column anim-fade-in fast Box--overlay overflow-visible"
      aria-label="Provide feedback"
      src="/btrich011/Brian_Rich_Capstone/repos/code_nav_survey"
      
    >
    <div class="Box-header">
      <button class="Box-btn-octicon btn-octicon float-right" type="button" aria-label="Close dialog" data-close-dialog>
        <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-x">
    <path d="M3.72 3.72a.75.75 0 0 1 1.06 0L8 6.94l3.22-3.22a.749.749 0 0 1 1.275.326.749.749 0 0 1-.215.734L9.06 8l3.22 3.22a.749.749 0 0 1-.326 1.275.749.749 0 0 1-.734-.215L8 9.06l-3.22 3.22a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042L6.94 8 3.72 4.78a.75.75 0 0 1 0-1.06Z"></path>
</svg>
      </button>
        <h1 class="Box-title" >Provide feedback</h1>
    </div>
      <div class="Box-body overflow-auto">
                  <include-fragment>
            <svg style="box-sizing: content-box; color: var(--color-icon-primary);" width="32" height="32" viewBox="0 0 16 16" fill="none" data-view-component="true" class="my-3 mx-auto d-block anim-rotate">
  <circle cx="8" cy="8" r="7" stroke="currentColor" stroke-opacity="0.25" stroke-width="2" vector-effect="non-scaling-stroke" />
  <path d="M15 8a7.002 7.002 0 00-7-7" stroke="currentColor" stroke-width="2" stroke-linecap="round" vector-effect="non-scaling-stroke" />
</svg>
          </include-fragment>

      </div>
  </details-dialog>
</details>
    </div>
</div>

  </div>


  </div>

</turbo-frame>


    </main>
  </div>

  </div>

          <footer class="footer width-full container-xl p-responsive" role="contentinfo">
  <h2 class='sr-only'>Footer</h2>

  <div class="position-relative d-flex flex-items-center pb-2 f6 color-fg-muted border-top color-border-muted flex-column-reverse flex-lg-row flex-wrap flex-lg-nowrap mt-6 pt-6">
    <div class="list-style-none d-flex flex-wrap col-0 col-lg-2 flex-justify-start flex-lg-justify-between mb-2 mb-lg-0">
      <div class="mt-2 mt-lg-0 d-flex flex-items-center">
        <a aria-label="Homepage" title="GitHub" class="footer-octicon mr-2" href="https://github.com">
          <svg aria-hidden="true" height="24" viewBox="0 0 16 16" version="1.1" width="24" data-view-component="true" class="octicon octicon-mark-github">
    <path d="M8 0c4.42 0 8 3.58 8 8a8.013 8.013 0 0 1-5.45 7.59c-.4.08-.55-.17-.55-.38 0-.27.01-1.13.01-2.2 0-.75-.25-1.23-.54-1.48 1.78-.2 3.65-.88 3.65-3.95 0-.88-.31-1.59-.82-2.15.08-.2.36-1.02-.08-2.12 0 0-.67-.22-2.2.82-.64-.18-1.32-.27-2-.27-.68 0-1.36.09-2 .27-1.53-1.03-2.2-.82-2.2-.82-.44 1.1-.16 1.92-.08 2.12-.51.56-.82 1.28-.82 2.15 0 3.06 1.86 3.75 3.64 3.95-.23.2-.44.55-.51 1.07-.46.21-1.61.55-2.33-.66-.15-.24-.6-.83-1.23-.82-.67.01-.27.38.01.53.34.19.73.9.82 1.13.16.45.68 1.31 2.69.94 0 .67.01 1.3.01 1.49 0 .21-.15.45-.55.38A7.995 7.995 0 0 1 0 8c0-4.42 3.58-8 8-8Z"></path>
</svg>
</a>        <span>
        &copy; 2023 GitHub, Inc.
        </span>
      </div>
    </div>

    <nav aria-label='Footer' class="col-12 col-lg-8">
      <h3 class='sr-only' id='sr-footer-heading'>Footer navigation</h3>
      <ul class="list-style-none d-flex flex-wrap col-12 flex-justify-center flex-lg-justify-between mb-2 mb-lg-0" aria-labelledby='sr-footer-heading'>
          <li class="mr-3 mr-lg-0"><a href="https://docs.github.com/site-policy/github-terms/github-terms-of-service" data-analytics-event="{&quot;category&quot;:&quot;Footer&quot;,&quot;action&quot;:&quot;go to terms&quot;,&quot;label&quot;:&quot;text:terms&quot;}">Terms</a></li>
          <li class="mr-3 mr-lg-0"><a href="https://docs.github.com/site-policy/privacy-policies/github-privacy-statement" data-analytics-event="{&quot;category&quot;:&quot;Footer&quot;,&quot;action&quot;:&quot;go to privacy&quot;,&quot;label&quot;:&quot;text:privacy&quot;}">Privacy</a></li>
          <li class="mr-3 mr-lg-0"><a data-analytics-event="{&quot;category&quot;:&quot;Footer&quot;,&quot;action&quot;:&quot;go to security&quot;,&quot;label&quot;:&quot;text:security&quot;}" href="https://github.com/security">Security</a></li>
          <li class="mr-3 mr-lg-0"><a href="https://www.githubstatus.com/" data-analytics-event="{&quot;category&quot;:&quot;Footer&quot;,&quot;action&quot;:&quot;go to status&quot;,&quot;label&quot;:&quot;text:status&quot;}">Status</a></li>
          <li class="mr-3 mr-lg-0"><a data-ga-click="Footer, go to help, text:Docs" href="https://docs.github.com">Docs</a></li>
          <li class="mr-3 mr-lg-0"><a href="https://support.github.com?tags=dotcom-footer" data-analytics-event="{&quot;category&quot;:&quot;Footer&quot;,&quot;action&quot;:&quot;go to contact&quot;,&quot;label&quot;:&quot;text:contact&quot;}">Contact GitHub</a></li>
          <li class="mr-3 mr-lg-0"><a href="https://github.com/pricing" data-analytics-event="{&quot;category&quot;:&quot;Footer&quot;,&quot;action&quot;:&quot;go to Pricing&quot;,&quot;label&quot;:&quot;text:Pricing&quot;}">Pricing</a></li>
        <li class="mr-3 mr-lg-0"><a href="https://docs.github.com" data-analytics-event="{&quot;category&quot;:&quot;Footer&quot;,&quot;action&quot;:&quot;go to api&quot;,&quot;label&quot;:&quot;text:api&quot;}">API</a></li>
        <li class="mr-3 mr-lg-0"><a href="https://services.github.com" data-analytics-event="{&quot;category&quot;:&quot;Footer&quot;,&quot;action&quot;:&quot;go to training&quot;,&quot;label&quot;:&quot;text:training&quot;}">Training</a></li>
          <li class="mr-3 mr-lg-0"><a href="https://github.blog" data-analytics-event="{&quot;category&quot;:&quot;Footer&quot;,&quot;action&quot;:&quot;go to blog&quot;,&quot;label&quot;:&quot;text:blog&quot;}">Blog</a></li>
          <li><a data-ga-click="Footer, go to about, text:about" href="https://github.com/about">About</a></li>
      </ul>
    </nav>
  </div>

  <div class="d-flex flex-justify-center pb-6">
    <span class="f6 color-fg-muted"></span>
  </div>
</footer>
=======
females per generation.

References
Levin, M. L., & Schumacher, L. B. (2016). Manual for maintenance of multi-host ixodid ticks in the laboratory.
Experimental and Applied Acarology, 70(3), 343–367. https://doi.org/10.1007/s10493-016-0084-8
Maramorosch, K., Mahmood, F. E., & Sonenshine, D. E. (1999). Maintenance of Ticks in the Laboratory. In
Maintenance of human, animal, and plant pathogen vectors. essay, Science Publishers.
Needham, G. R., & Teel, P. D. (1991). Off-host physiological ecology of ixodid ticks. Annual Review of
Entomology, 36(1), 659–681. https://doi.org/10.1146/annurev.en.36.010191.003303
Wang, H.-H., Corson, M. S., Grant, W. E., & Teel, P. D. (2017). Quantitative models of rhipicephalus (boophilus)
ticks: Historical Review and synthesis. Ecosphere, 8(9). https://doi.org/10.1002/ecs2.1942 
>>>>>>> 1201491bbcfc8165d97bc61ac1e5a1eed7216335




<<<<<<< HEAD
  <div id="ajax-error-message" class="ajax-error-message flash flash-error" hidden>
    <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-alert">
    <path d="M6.457 1.047c.659-1.234 2.427-1.234 3.086 0l6.082 11.378A1.75 1.75 0 0 1 14.082 15H1.918a1.75 1.75 0 0 1-1.543-2.575Zm1.763.707a.25.25 0 0 0-.44 0L1.698 13.132a.25.25 0 0 0 .22.368h12.164a.25.25 0 0 0 .22-.368Zm.53 3.996v2.5a.75.75 0 0 1-1.5 0v-2.5a.75.75 0 0 1 1.5 0ZM9 11a1 1 0 1 1-2 0 1 1 0 0 1 2 0Z"></path>
</svg>
    <button type="button" class="flash-close js-ajax-error-dismiss" aria-label="Dismiss error">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-x">
    <path d="M3.72 3.72a.75.75 0 0 1 1.06 0L8 6.94l3.22-3.22a.749.749 0 0 1 1.275.326.749.749 0 0 1-.215.734L9.06 8l3.22 3.22a.749.749 0 0 1-.326 1.275.749.749 0 0 1-.734-.215L8 9.06l-3.22 3.22a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042L6.94 8 3.72 4.78a.75.75 0 0 1 0-1.06Z"></path>
</svg>
    </button>
    You can’t perform that action at this time.
  </div>

  <div class="js-stale-session-flash flash flash-warn flash-banner" hidden
    >
    <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-alert">
    <path d="M6.457 1.047c.659-1.234 2.427-1.234 3.086 0l6.082 11.378A1.75 1.75 0 0 1 14.082 15H1.918a1.75 1.75 0 0 1-1.543-2.575Zm1.763.707a.25.25 0 0 0-.44 0L1.698 13.132a.25.25 0 0 0 .22.368h12.164a.25.25 0 0 0 .22-.368Zm.53 3.996v2.5a.75.75 0 0 1-1.5 0v-2.5a.75.75 0 0 1 1.5 0ZM9 11a1 1 0 1 1-2 0 1 1 0 0 1 2 0Z"></path>
</svg>
    <span class="js-stale-session-flash-signed-in" hidden>You signed in with another tab or window. <a href="">Reload</a> to refresh your session.</span>
    <span class="js-stale-session-flash-signed-out" hidden>You signed out in another tab or window. <a href="">Reload</a> to refresh your session.</span>
  </div>
    <template id="site-details-dialog">
  <details class="details-reset details-overlay details-overlay-dark lh-default color-fg-default hx_rsm" open>
    <summary role="button" aria-label="Close dialog"></summary>
    <details-dialog class="Box Box--overlay d-flex flex-column anim-fade-in fast hx_rsm-dialog hx_rsm-modal">
      <button class="Box-btn-octicon m-0 btn-octicon position-absolute right-0 top-0" type="button" aria-label="Close dialog" data-close-dialog>
        <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-x">
    <path d="M3.72 3.72a.75.75 0 0 1 1.06 0L8 6.94l3.22-3.22a.749.749 0 0 1 1.275.326.749.749 0 0 1-.215.734L9.06 8l3.22 3.22a.749.749 0 0 1-.326 1.275.749.749 0 0 1-.734-.215L8 9.06l-3.22 3.22a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042L6.94 8 3.72 4.78a.75.75 0 0 1 0-1.06Z"></path>
</svg>
      </button>
      <div class="octocat-spinner my-6 js-details-dialog-spinner"></div>
    </details-dialog>
  </details>
</template>

    <div class="Popover js-hovercard-content position-absolute" style="display: none; outline: none;" tabindex="0">
  <div class="Popover-message Popover-message--bottom-left Popover-message--large Box color-shadow-large" style="width:360px;">
  </div>
</div>

    <template id="snippet-clipboard-copy-button">
  <div class="zeroclipboard-container position-absolute right-0 top-0">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn js-clipboard-copy m-2 p-0 tooltipped-no-delay" data-copy-feedback="Copied!" data-tooltip-direction="w">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon m-2">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none m-2">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div>
</template>


    <style>
      .user-mention[href$="/btrich011"] {
        color: var(--color-user-mention-fg);
        background-color: var(--color-user-mention-bg);
        border-radius: 2px;
        margin-left: -2px;
        margin-right: -2px;
        padding: 0 2px;
      }
    </style>


    </div>

    <div id="js-global-screen-reader-notice" class="sr-only" aria-live="polite" ></div>
  </body>
</html>

=======
# Objective

Use an unsupervised machine learning method to analyze 63 generations of tick drop data from colony raised "Rhipicephalus (Boophilus) microplus".  Kmeans will be utilized here for the initial analysis.

### Dataset 
  Tick drop data was obtained from USDA ARS' Cattle Fever Research Laboratory in Edinburg, TX.
### Python version and packages

* Python version 3.10.9
* All the packages/versions used for this project can be found in [Requirements](https://github.com/btrich011/Brian_Rich_Capstone/blob/main/requirements.txt) file.
>>>>>>> 1201491bbcfc8165d97bc61ac1e5a1eed7216335
