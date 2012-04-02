graphite: python /opt/graphite/webapp/graphite/manage.py run_gunicorn -b 0.0.0.0:3031 -w 3
carbon: python /opt/graphite/bin/carbon-cache.py --debug start
stats: node /usr/local/src/statsd/stats.js statsConfig.js 
