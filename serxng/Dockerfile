FROM searxng/searxng:2026.6.22-952896d29

RUN sed -i '/- html/a \    - json' /usr/local/searxng/searx/settings.yml
RUN sed -i 's/request_timeout: 3.0/request_timeout: 10.0/g' /usr/local/searxng/searx/settings.yml
