<template>
    <b-footer
      padding="y-4 y-md-5"
      margin="t-5"
      background-color="body-tertiary"
      class="bd-footer"
    >
      <Container
        type="xl"
        padding="y-4 y-md-5 x-4 x-md-3"
        text-color="body-secondary"
      >
        <Row>
          <Col
            col="lg-3"
            margin="b-3"
          >
            <b-a
              display="inline-flex"
              margin="b-2"
              text-color="body-emphasis"
              text-decoration="none"
              href="/"
              aria-label="use-bootstrap"
            >
              <img
                src="~/assets/img/logo1.svg"
                alt="use-bootstrap"
                height="30"
              >
            </b-a>
            <b-ul
              unstyled
              small
            >
              <b-li margin="b-2">
                ここはリンクに飛べるところだよ
              </b-li>
              <b-li margin="b-2">
                tawa company
              </b-li>
            </b-ul>
          </Col>
          <Col
            col="6 lg-2"
            offset="lg-1"
            margin="b-3"
          >
            <b-h level="5">Links</b-h>
            <b-ul unstyled>
              <b-li margin="b-2">
                <b-a text-color="body-secondary" link-underline="0 100-hover dark" href="/">Home</b-a>
              </b-li>
            </b-ul>
          </Col>
          <Col
            col="6 lg-2"
            margin="b-3"
          >
            <b-h level="5">bereal</b-h>
            <b-ul unstyled>
              <b-li margin="b-2">
                <b-a text-color="body-secondary" link-underline="0 100-hover dark" href="https://bere.al/tawashi0624">ここおして</b-a>
              </b-li>
            </b-ul>
          </Col>
          <Col
            col="6 lg-2"
            margin="b-3"
          >
            <b-h level="5">インスタ</b-h>
            <b-ul unstyled>
              <b-li margin="b-2">
                <b-a text-color="body-secondary" link-underline="0 100-hover dark" href="https://www.instagram.com/tako_chiko.0624?igsh=OHF1N3kyeXN5bTNt&utm_source=qr">ここ押してね</b-a>
              </b-li>
            </b-ul>
          </Col>
        </Row>
      </Container>
    </b-footer>
  </template>