from django.conf.urls.defaults import *
from bookmarks.views import *
from django.contrib import admin

admin.autodiscover()

urlpatterns = patterns('',
	(r'^$',main_page),
	(r'^user/(\w+)/$',user_page),
	(r'^admin/', include(admin.site.urls)),
	(r'^login/$','django.contrib.auth.views.login'),

)
