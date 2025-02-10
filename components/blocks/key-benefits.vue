<template>
    <Block text-alignment="center">
        <b-h level="2">
            好きなジャンル
        </b-h>
    </Block>
    <Row gutter="x-3" columns="1 md-2">
        <Col>
        <Card relative-height="100" class="un-transition-all un-ease-in-out hover:-un-translate-y-0.5"
            background-color="transparent">
            <Background img-src="/unsplash/image/480x220/dlxmedia-hu-U-W8FKeC6Mo-unsplash.jpg" relative-height="100"
                :overlay="true" overlay-color="white" overlay-alpha="0.6" :img-parallax="0.1" rounded>
                <CardBody>
                    <CardTitle text-color="dark" headings="1">
                        アニメジャンル一覧
                    </CardTitle>
                    <CardText text-color="dark">
                        皆さんの好きなジャンルはなんですか？
                    </CardText>
                </CardBody>
                <CardFooter>
                    <CardLink stretched-link to="https://animestore.docomo.ne.jp/animestore/gen_sel_pc">
                        ジャンルの種類
                        <BIcon margin="s-1" small icon="bi:chevron-right" />
                    </CardLink>
                </CardFooter>
            </Background>
        </Card>
        </Col>

        <Col padding="y-3">
        <Row>
            <Col col="md-6">
            <b-h level="4">
                恋愛系アニメ
            </b-h>
            <b-p text-color="secondary">
                はらはらドキドキします
            </b-p>
            </Col>

            <Col col="md-6">
            <BIcon icon="bi:bar-chart-fill" text-color="primary" font-size="2" />
            <b-h level="4">
                ほのぼの系
            </b-h>
            <b-p text-color="secondary">
                田舎の良さに気づかされます！
            </b-p>
            </Col>

            <Col col="md-6">
            <BIcon icon="bi:lightbulb-fill" text-color="primary" font-size="2" />
            <b-h level="4">
                バトル系
            </b-h>
            <b-p text-color="secondary">
                たまに見るとちょっとあこがれる！
            </b-p>
            </Col>

            <Col col="md-6">
            <BIcon icon="bi:lightning-charge-fill" text-color="primary" font-size="2" />
            <b-h level="4">
                青春系
            </b-h>
            <b-p text-color="secondary">
                学生に戻りたくなります。
            </b-p>
            </Col>
        </Row>
        </Col>
    </Row>
</template>