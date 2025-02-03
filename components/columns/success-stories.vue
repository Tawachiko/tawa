<template>
    <Block
     size="8"
     text-alignment="center"
     margin="y-3"
    >
     <b-div headings="2">
      おすすめのアニメ配信サイト
     </b-div>
    </Block>
   
    <Row
     margin="b-3"
     columns="1 md-3"
    >
     <Col>
      <Card relative-height="100">
       <CardImgTop
        src="/selfimg/netflix.jpg"
        alt="Image Description"
       />
   
       <CardBody>
        <b-div margin="b-3">
        </b-div>
        <CardText>アニメ以外にも見れておすすめです</CardText>
       </CardBody>
   
       <CardFooter>
        <CardLink
         icon="bi:chevron-right"
         icon-end
         to="https://www.netflix.com/jp/"
         stretched-link
        >
         インストール
        </CardLink>
       </CardFooter>
      </Card>
     </Col>
   
     <Col>
      <Card relative-height="100">
       <CardImgTop
        src="/selfimg/d-anime.png"
        alt="Image Description"
       />
   
       <CardBody>
        <b-div margin="b-3">
        </b-div>
        <CardText> アニメ数なら多分一番です</CardText>
       </CardBody>
   
       <CardFooter>
        <CardLink
         icon="bi:chevron-right"
         icon-end
         to="https://animestore.docomo.ne.jp/animestore/tp_pc"
         stretched-link
        >
         インストール
        </CardLink>
       </CardFooter>
      </Card>
     </Col>
   
     <Col>
      <Card relative-height="100">
       <CardImgTop
        src="/selfimg/anime-houdai.jpg"
        alt="Image Description"
       />
   
       <CardBody>
        <b-div margin="b-3">
        </b-div>
        <CardText>U-NEXTと連携しているのでアニメ数多いです！</CardText>
       </CardBody>
   
       <CardFooter>
        <CardLink
         icon="bi:chevron-right"
         icon-end
         to="https://www.animehodai.jp/"
         stretched-link
        >
         インストール
        </CardLink>
       </CardFooter>
      </Card>
     </Col>
    </Row>
    <Block
     size="md-4"
    >
    </Block>
   </template>
   