FROM node:13.10-alpine

RUN apk update && apk upgrade && \
    apk add --no-cache bash git openssh
# RUN npx degit sveltejs/template project && \
#     cd project && \
#     yarn

#EXPOSE 5000

# Start application
CMD ["yarn", "dev"]