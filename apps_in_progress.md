# Apps in progress

<a class="btn btn-lg btn-default" href="/apps_en">Official apps</a> <a class="btn btn-lg btn-default disabled" href="/apps_in_progress_en">Apps in progress</a> <a class="btn btn-lg btn-default" href="/apps_wishlist_en">Apps wishlist</a>

The following applications are being packaged on by a growing number of packagers.
<div class="alert alert-danger">They are **NOT** validated by the packaging team, and as such, **no official support is provided** for them.<br>
You can test and use them **at your own risk**.
</div>

You can install them through the [administration web interface](/admin) by choosing "Install custom app", or using the [moulinette](/moulinette):
```bash
yunohost app install https://github.com/<packager>/<app_repository>
```

The packagers will appreciate your remarks. If you test them and find issues, or ideas for improvement, do not hesitate to file issues directly on their repositories project page.

<br>

<div class="panel-group" id="app-accordion2"></div>

<script type="text/template" id="app-template2">
  <div class="panel panel-default">
    <div class="panel-heading">
      <div class="panel-title">
        <a data-toggle="collapse" data-parent="#app-accordion" href="#app_{app_id}">{app_name} <em><small>({app_id})</small></em></a>
      </div>
    </div>
    <div class="panel-collapse collapse app_{app_id}">
      <div class="panel-body">
        <p><strong>Description</strong>: {app_description}</p>
        <p><strong>Last update (UTC)</strong>: {app_update}</p>
        <p><strong>Maintainer</strong>: {app_maintainer} <small class="text-muted">({app_mail})</small></p>
        <p><strong>Git</strong>: <a href="{app_git}" target="_blank">{app_git}</a> <small class="text-muted">({app_branch})</small></p>
        <div class="{app_state}"/>
    </div>
  </div>
</script>
