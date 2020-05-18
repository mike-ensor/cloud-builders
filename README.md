# Google Cloud Build official builder images

This repository contains source code for official builders used with the [Google
Cloud Build API](https://cloud.google.com/cloud-build/docs/).

Pre-built images are available at `gcr.io/cloud-builders/...` and include:

*   `git`: runs the [git](https://git-scm.com/) tool
*   `go`: runs the [go](https://golang.org/cmd/go) tool
*   `wget`: runs the [wget](https://www.gnu.org/software/wget/) tool

Builders contributed by the public are available in the [Cloud Builders
Community
repo](https://github.com/GoogleCloudPlatform/cloud-builders-community).

To file issues and feature requests against these builder images,
[create an issue in this repo](https://github.com/GoogleCloudPlatform/cloud-builders/issues/new).
If you are experiencing an issue with the Cloud Build service or
have a feature request, e-mail google-cloud-dev@googlegroups.com
or see our [Getting support](https://cloud.google.com/cloud-build/docs/getting-support)
documentation.

---

# Deprecated Images

The following builders in this repo are deprecated and will be deleted in the future:

*   Replaced by [`docker`](https://hub.docker.com/_/docker/) image:
    *   `docker`: runs the [docker](https://docker.com) tool
*   Replaced by [`gcr.io/google.com/cloudsdktool/cloud-sdk`](https://github.com/GoogleCloudPlatform/cloud-sdk-docker) image:
    *   `gcloud`: runs the [gcloud](https://cloud.google.com/sdk/gcloud/) tool
    *   `gsutil`: runs the [gsutil](https://cloud.google.com/storage/docs/gsutil) tool
    *   `kubectl`: runs the [kubectl](https://kubernetes.io/docs/user-guide/kubectl-overview/) tool
*   Replaced by the [`node`](https://hub.docker.com/_/node) image:
    *   `npm`: runs the [npm](https://docs.npmjs.com/) tool
    *   `yarn`: runs the [yarn](https://yarnpkg.com/) tool
*   Replaced by [`microsoft/dotnet:sdk`](https://hub.docker.com/_/microsoft-dotnet-core):
    *   `dotnet`: runs the [dotnet](https://docs.microsoft.com/dotnet/core/tools/) tool
*   Replaced by [`openjdk`](https://hub.docker.com/_/openjdk)
    *   `javac`: runs the [javac](https://docs.oracle.com/javase/7/docs/technotes/tools/windows/javac.html) tool
*   Replaced by [`gradle`](https://hub.docker.com/_/gradle/):
    *   `gradle`: runs the [gradle](https://gradle.org/) tool
*   Replaced by [`maven`](https://hub.docker.com/_/maven/):
    *   `mvn`: runs the [maven](https://maven.apache.org/) tool
*   Replaced by [`gcr.io/cloud-marketplace-containers/google/bazel`](http://gcr.io/cloud-marketplace-containers/google/bazel):
    *   `bazel`: runs the [bazel](https://bazel.io) tool
*   Replaced by [`launcher.gcr.io/google/ubuntu1604`](https://console.cloud.google.com/launcher/details/google/ubuntu1604) or [`curlimages/curl`](https://hub.docker.com/r/curlimages/curl):
	*   `curl`: runs the [curl](https://curl.haxx.se) tool
