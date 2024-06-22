FROM almalinux:9
CMD ["ping","-c5","google.com"] 
# this is overriden

# ENTRYPOINT ["ping", "-c5", "google.com"] # this is appended

# case3: mix of both entrypoint,CMD......CMD can provide default value
#CMD ["google.com"]
# ENTRYPOINT ["ping", "-c5"]