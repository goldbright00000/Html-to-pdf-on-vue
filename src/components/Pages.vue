<template>
    <section>
        <button class="btn" @click="makePdf">make pdf</button>
        <div class="first-page page">
            <div class="header">
                <div class="header-top"><p>Data/Cliente/Projeto/Cotação<span style="display: block;font-size: 14px">Rio de Janeiro, 2020/02/05</span>
                </p></div>
                <div class="header-main cols">
                    <div class="col"><p>Cliente: Craveiro's Ltda <span>Endereço: undefined</span></p></div>
                    <div class="col"><p class="text-ac">Projeto: Bomba OH2 para petróleo</p></div>
                </div>
                <div class="header-footer flex j-cc">
                    <strong>Cotação Nº *quote-number </strong>
                </div>
            </div>
            <main class="main">
                <article class="article">
                    <p class="title">POLÍTICA DE QUALIDADE RP:</p>
                    <p>A Flopo do Brasil Ltda compromete-se em estabelecer e melhorar continuamente a qualidade dos
                        seus
                        produtos e serviços visando atender plenamente seus clientes, acionistas e colaboradores. A
                        gestão
                        de qualidade da empresa baseia-se em fornecimento de produtos de alta tecnologia,
                        capacitação
                        profissional, respeito mútuo e crescimento contínuo. </p>
                </article>
                <article class="article">
                    <p class="title">ESCOPO DE FORNECIMENTO:</p>
                    <p>
                        A Ruhrpumpen é uma empresa multinacional, com plantas de fabricação em vários países, e como
                        tal,
                        poderemos utilizar abastecimento global para apoiar o processo de fabricação. Nosso preço
                        baseia-se
                        estritamente no escopo de fornecimento descrito nesta proposta. Equipamentos ou acessórios
                        adicionais, não mencionados no escopo de fornecimento, serão orçados separadamente. Entre em
                        contato
                        com a Ruhrpumpen para consulta de itens adicionais, prazos de entrega e preços.
                    </p>
                </article>
            </main>
        </div>
        <div class="second-page page">
            <div class="container">
                <div class="title-header"><p>ESPECIFICAÇÕES:</p></div>
                <article class="article">
                    <p class="title">VALIDADE:</p>
                    <p>*Esta proposta é valida por 30 dias a partir da data da emissão. Para pedidos com "espera
                        para
                        aprovação" da documentação, os preços cotados permanecerão firmes até a data de embarque, se
                        a
                        liberação para fabricação pelo cliente não ultrapassar 30 dias da data de envio para
                        aprovação.
                        Caso contrario, poderá ser aplicado um acréscimo nos preços e a postergação do prazo de
                        entrega.</p>
                </article>
                <article class="article">
                    <p class="title">IMPOSTOS:</p>
                    <p>Alíquota de 12% com carga tributária de 8,80% para o estado de Minas Gerais, Paraná, Rio
                        Grande
                        do Sul, Rio de Janeiro, Santa Catarina e São Paulo. Sendo que para saídas e faturamento a
                        partir
                        do estado de São Paulo e Rio de Janeiro, a alíquota do ICMS está em conformidade com a
                        “RESOLUÇÃO SF4/98”. Esta oferta contempla o benefício de redução na base de cálculo do ICMS
                        para
                        bombas centrífugas conforme Convênios ICMS nº 52/91. </p>
                </article>
                <article class="article">
                    <p class="title">
                        TERMOS E CONDIÇÕES:</p>
                    <p>Os Termos e Condições Globais de Vendas da Ruhrpumpen são aplicáveis para essa cotação e são
                        anexados para sua referência. Desvios específicos mencionados nesta carta de apresentação de
                        cotação e/ou quaisquer outros desvios listados dentro do nosso orçamento podem contradizer
                        estes
                        termos e, em caso afirmativo, substituirão o item específico dos Termos e Condições de
                        Compra
                        Global da Ruhrpumpen. </p>
                </article>
                <article class="article">
                    <p>Assinatura</p>
                </article>
            </div>
        </div>
        <div class="third-page page flex j-cc a-ic">
            <h1 class="h1">Price <br>Sheet</h1>
        </div>

        <div class="fourth-page page landscape flex j-cc">
            <table class="table" id="myTable">
                <thead>
                <tr>
                    <th>S.No</th>
                    <th>Tag</th>
                    <th>Service</th>
                    <th>Product Description</th>
                    <th>Unit Price</th>
                    <th>Qty</th>
                    <th>Extend Price</th>
                </tr>
                </thead>
                <tbody>
                <tr>
                    <td>1</td>
                    <td>B-2351104A/C</td>
                    <td>Water</td>
                    <td>Bomba Click Pump | Size: Modelo Click</td>
                    <td>3600</td>
                    <td>3</td>
                    <td>10800</td>
                </tr>
                <tr>
                    <td>2</td>
                    <td>007</td>
                    <td>Water Sub</td>
                    <td>SCE | Size: SCE 10x8x18</td>
                    <td>10108</td>
                    <td>2</td>
                    <td>20216</td>
                </tr>
                <tr>
                    <td>3</td>
                    <td>010</td>
                    <td>Water sub water</td>
                    <td>VCT - KX | Size: Bomba vertical VCT - Novo teste</td>
                    <td>4028</td>
                    <td>4</td>
                    <td>16112</td>
                </tr>
                </tbody>
            </table>
        </div>


        <div class="fifth-page page flex j-cc a-ic">
            <h1 class="h1">Scope of<br> Supply</h1>
        </div>
        <div class="six-page page">
            <table class="table" id="table2">
                <caption>Scope of Supply</caption>
                <tbody>
                <tr>
                    <th>Customer</th>
                    <th></th>
                    <th>Service</th>
                    <td>Water</td>
                </tr>
                <tr>
                    <th>Item number</th>
                    <td>B-2351104A/C</td>
                    <th>Customer Reference</th>
                    <td>N/A</td>
                </tr>
                <tr>
                    <th>Pump Size</th>
                    <td>Modelo Click</td>
                    <th>Quote Number</th>
                    <td>008RJBR</td>
                </tr>
                </tbody>
            </table>
            <table class="table tType" id="table3">
                <caption>B-2351104A/C - Bomba Click Pump | Size: Modelo Click</caption>
                <tbody>
                <tr>
                    <th>Qty</th>
                    <th>Description</th>
                </tr>
                <tr class="is-border">
                    <td></td>
                    <th style="padding-top: 32px">Casing</th>
                </tr>
                <tr>
                    <td>3</td>
                    <td>Cast Iron</td>
                </tr>
                <tr class="is-border">
                    <th></th>
                    <th>Impeller</th>
                </tr>
                <tr>
                    <td>5</td>
                    <td>Cast Iron</td>
                </tr>
                </tbody>
            </table>
        </div>
        <div class="seven-page page">
            <table class="table" id="table4">

                <caption>Scope of Supply</caption>

                <tbody>
                <tr>
                    <td style="font-weight: bold">Customer</td>
                    <td></td>
                    <td>Service</td>
                    <td>Water Sub</td>
                </tr>
                <tr>
                    <td>Item number</td>
                    <td>007</td>
                    <td>Customer Reference</td>
                    <td>N/A</td>
                </tr>
                <tr>
                    <td>Pump Size</td>
                    <td>SCE 10x8x18</td>
                    <td>Quote Number</td>
                    <td>008RJBR</td>
                </tr>
                </tbody>
            </table>
            <table class="table tType" id="table5">
                <caption>007 - SCE | Size: SCE 10x8x18</caption>
                <tbody>
                <tr>
                    <th>Qty</th>
                    <th>Description</th>
                </tr>
                <tr class="is-border">
                    <td></td>
                    <th style="padding-top: 32px">Carcaca</th>
                </tr>
                <tr class="is-border">
                    <td>7</td>
                    <td>Duplex</td>
                </tr>
                </tbody>
            </table>
        </div>
        <div class="eight-page page">
            <table class="table" id="table6">
                <caption>Scope of Supply</caption>
                <tbody>
                <tr>
                    <th>Customer</th>
                    <th></th>
                    <th>Service</th>
                    <td>Water</td>
                </tr>
                <tr>
                    <th>Item number</th>
                    <td>010</td>
                    <th>Customer Reference</th>
                    <td>N/A</td>
                </tr>
                <tr>
                    <th>Pump Size</th>
                    <td>Bomba vertical VCT - Novo teste</td>
                    <th>Quote Number</th>
                    <td>008RJBR</td>
                </tr>
                </tbody>
            </table>
            <table class="table tType" id="table7">
                <caption>010 - VCT - KX | Size: Bomba vertical VCT - Novo teste</caption>
                <tbody>
                <tr>
                    <th>Qty</th>
                    <th>Description</th>
                </tr>
                <tr class="is-border">
                    <td></td>
                    <th style="padding-top: 32px">Carcaca</th>
                </tr>
                <tr>
                    <td>2</td>
                    <td>Duplex</td>
                </tr>
                <tr class="is-border">
                    <th></th>
                    <th>Mancal</th>
                </tr>
                <tr>
                    <td>2</td>
                    <td>MANCAL Y FY 504 M - SKF</td>
                </tr>
                <tr>
                    <td>3</td>
                    <td>MANCAL Y FY 512 M - SKF</td>
                </tr>
                <tr class="is-border">
                    <th></th>
                    <th>Rolamento</th>
                </tr>
                <tr class="is-border">
                    <td>2</td>
                    <td>ROLAMENTO RÍGIDO DE ESFERAS 6205/2ZC3 - SKF</td>
                </tr>
                </tbody>
            </table>
        </div>
        <div class="nine page flex j-cc a-ic">
            <h1 class="h1">Datasheet</h1>
        </div>

        <div class="ten page landscape">
            <div class="text-ac">
                <p><strong>Tag: B-2351104A/C - </strong>Bomba Click Pump | Size: Modelo Click </p>
            </div>
            <table class="table text-al">
                <thead class="tStrong">Pump Information</thead>
                <tbody>
                <tr>
                    <th>Tag:</th>
                    <td>B-2351104A/C</td>
                </tr>
                <tr>
                    <th>Quantity:</th>
                    <td>3</td>
                </tr>
                <tr>
                    <th>Line:</th>
                    <td>Bomba Click Pump</td>
                </tr>
                <tr>
                    <th>Size:</th>
                    <td>Modelo Click</td>
                </tr>
                <tr>
                    <th>Service:</th>
                    <td>Water</td>
                </tr>
                </tbody>
            </table>
            <table class="table text-al">
                <thead class="tStrong">Duty Conditions</thead>
                <tbody>
                <tr>
                    <th>
                        Flow:
                    </th>
                    <td>200.00 m3/h</td>
                    <th>NPSHa:</th>
                    <td>49.6 m</td>
                    <th>Liquid:</th>
                </tr>
                <tr>
                    <th>Head:</th>
                    <td>755.8 m</td>
                    <th>Suction Pressure:</th>
                    <td>(0/0/1.01325) ft</td>
                    <th>Temperature:</th>
                    <td>(60/60/60) C</td>
                </tr>
                <tr>
                    <th>Frequency:</th>
                    <td>60Hz/3585 RPM</td>
                    <th>vapor Pressure:</th>
                    <td>(//) ft</td>
                    <th>Sphere Diameter Size:</th>
                </tr>
                <tr>
                    <th>Speed Criteria:</th>
                    <td>All Suitable Asyc Speed</td>
                    <th>Density:</th>
                    <td>(0/0/1.04) S.G.</td>
                    <th>Solids Con by Vol:</th>
                    <td>00</td>
                </tr>
                <tr>
                    <th>Pump Operation:</th>
                    <td>-</td>
                    <th>Viscosity:</th>
                    <td>3.46 cP</td>
                    <th> Cq/Ch/Ce/Cn:</th>
                    <td>1.00/1.00/1.00/1.00</td>
                </tr>
                </tbody>
            </table>
            <table class="table text-al">
                <thead class="tStrong">Performance Details</thead>
                <tbody>
                <tr>
                    <th>Rated Flow: <span class="span">200 m3/h (78.38%)</span></th>
                    <th>Differential Head (Hr):<span class="span">755.8 m </span></th>
                    <th>Hydraulic Power:<span class="span">427.62 kW</span></th>
                    <th>NPSHr:<span class="span">4.85 m</span></th>
                    <th>Dmax:<span class="span">11.42</span></th>
                </tr>
                <tr>
                    <th>Normal Flow: <span class="span">-</span></th>
                    <th>Shutoff Head:<span class="span">919.64 m</span></th>
                    <th>Rated Efficiency:<span class="span">73.61%</span></th>
                    <th>NPSHa - NPSHr:<span class="span">44.75 m</span></th>
                    <th>Drated:<span class="span">10.89</span></th>
                </tr>

                </tbody>
            </table>
        </div>

        <div class="eleven page flex j-cc a-ic">
            <h1 class="h1">Performance <br>Curves</h1>
        </div>

        <div class="page landscape">
            <div class="svg-wrap">
                <svg version="1.1" class="highcharts-root"
                     style="font-family:Lucida Grande,Lucida Sans Unicode, Arial, Helvetica, sans-serif;font-size:12px;"
                     xmlns="http://www.w3.org/2000/svg" width="1010" height="200"
                     viewBox="0 0 1010 200">
                    <desc>Created with Highcharts 6.2.0</desc>
                    <defs>
                        <clipPath id="highcharts-6mh5h5f-1951">
                            <rect x="0" y="0" width="930" height="165" fill="none"></rect>
                        </clipPath>
                    </defs>
                    <rect fill="#ffffff" class="highcharts-background" x="0" y="0" width="1010"
                          height="200" rx="0" ry="0"></rect>
                    <rect fill="none" class="highcharts-plot-background" x="70" y="10"
                          width="930" height="165"></rect>
                    <g class="highcharts-grid highcharts-xaxis-grid " data-z-index="1">
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 69.5 10 L 69.5 175"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 159.5 10 L 159.5 175"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 249.5 10 L 249.5 175"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 339.5 10 L 339.5 175"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 428.5 10 L 428.5 175"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 518.5 10 L 518.5 175"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 608.5 10 L 608.5 175"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 698.5 10 L 698.5 175"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 788.5 10 L 788.5 175"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 878.5 10 L 878.5 175"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 968.5 10 L 968.5 175"
                              opacity="1"></path>
                    </g>
                    <g class="highcharts-grid highcharts-yaxis-grid " data-z-index="1">
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 70 175.5 L 1000 175.5"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 70 120.5 L 1000 120.5"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 70 65.5 L 1000 65.5"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 70 9.5 L 1000 9.5"
                              opacity="1"></path>
                    </g>
                    <g class="highcharts-grid highcharts-yaxis-grid " data-z-index="1"></g>
                    <rect fill="none" class="highcharts-plot-border" data-z-index="1" x="70"
                          y="10" width="930" height="165"></rect>
                    <g class="highcharts-axis highcharts-xaxis " data-z-index="2">
                        <path fill="none" class="highcharts-tick" stroke="#ccd6eb"
                              stroke-width="1" d="M 69.5 175 L 69.5 185" opacity="1"></path>
                        <path fill="none" class="highcharts-tick" stroke="#ccd6eb"
                              stroke-width="1" d="M 159.5 175 L 159.5 185" opacity="1"></path>
                        <path fill="none" class="highcharts-tick" stroke="#ccd6eb"
                              stroke-width="1" d="M 249.5 175 L 249.5 185" opacity="1"></path>
                        <path fill="none" class="highcharts-tick" stroke="#ccd6eb"
                              stroke-width="1" d="M 339.5 175 L 339.5 185" opacity="1"></path>
                        <path fill="none" class="highcharts-tick" stroke="#ccd6eb"
                              stroke-width="1" d="M 428.5 175 L 428.5 185" opacity="1"></path>
                        <path fill="none" class="highcharts-tick" stroke="#ccd6eb"
                              stroke-width="1" d="M 518.5 175 L 518.5 185" opacity="1"></path>
                        <path fill="none" class="highcharts-tick" stroke="#ccd6eb"
                              stroke-width="1" d="M 608.5 175 L 608.5 185" opacity="1"></path>
                        <path fill="none" class="highcharts-tick" stroke="#ccd6eb"
                              stroke-width="1" d="M 698.5 175 L 698.5 185" opacity="1"></path>
                        <path fill="none" class="highcharts-tick" stroke="#ccd6eb"
                              stroke-width="1" d="M 788.5 175 L 788.5 185" opacity="1"></path>
                        <path fill="none" class="highcharts-tick" stroke="#ccd6eb"
                              stroke-width="1" d="M 878.5 175 L 878.5 185" opacity="1"></path>
                        <path fill="none" class="highcharts-tick" stroke="#ccd6eb"
                              stroke-width="1" d="M 968.5 175 L 968.5 185" opacity="1"></path>
                        <path fill="none" class="highcharts-axis-line" stroke="#ccd6eb"
                              stroke-width="1" data-z-index="7"
                              d="M 70 175.5 L 1000 175.5"></path>
                    </g>
                    <g class="highcharts-axis highcharts-yaxis " data-z-index="2">
                        <text x="23.015625" data-z-index="7" text-anchor="middle"
                              transform="translate(0,0) rotate(270 23.015625 92.5)"
                              class="highcharts-axis-title" style="color:#666666;fill:#666666;"
                              y="92.5">
                            <tspan>Power - hp</tspan>
                        </text>
                        <path fill="none" class="highcharts-axis-line" stroke="#ccd6eb"
                              stroke-width="1" data-z-index="7" d="M 69.5 10 L 69.5 175"></path>
                    </g>
                    <g class="highcharts-axis highcharts-yaxis " data-z-index="2">
                        <path fill="none" class="highcharts-axis-line" stroke="#ccd6eb"
                              stroke-width="1" data-z-index="7"
                              d="M 1000.5 10 L 1000.5 175"></path>
                    </g>
                    <g class="highcharts-series-group" data-z-index="3">
                        <g data-z-index="0.1"
                           class="highcharts-series highcharts-series-0 highcharts-spline-series highcharts-color-0 "
                           transform="translate(70,10) scale(1 1)"
                           clip-path="url(#highcharts-6mh5h5f-1951)">
                            <path fill="none"
                                  d="M 0 144.76749185358975 C 0 144.76749185358975 19.051837377997202 128.47712610308812 31.753062296662 123.08666396164986 C 44.4528494493184 117.6962018202116 50.8027430256466 118.2428301544742 63.502530178303 117.6962018202116 C 76.2037550969678 117.14957348594899 82.5543675563002 117.6962018202116 95.255592474965 117.14957348594899 C 107.955379627623 116.60294515168638 114.305273203952 115.29835820652448 127.00506035661 114.3145286438774 C 139.706285275274 113.3305877000958 146.056897734606 113.14209185155629 158.75812265327 112.23014721987732 C 171.45790980592602 111.31830581942219 177.807803382254 110.73824574650388 190.50759053491 109.75506356354214 C 203.208815453574 108.77177007273679 209.559427912906 108.29848889749503 222.26065283157 107.31395803545954 C 234.960439984226 106.32953862133684 241.310333560554 105.84202729771715 254.01012071321 104.83268787314663 C 266.711345631874 103.82323417942358 273.061958091206 103.29641313701507 285.76318300987 102.26697523972558 C 298.462970162526 101.23765387378056 304.812863738854 100.71979464157498 317.51265089151 99.68578971506035 C 330.21387581017797 98.65166772696652 336.564488269512 98.14236693846131 349.26571318818 97.09665795320446 C 361.965500340836 96.05106734116333 368.315393917164 95.52366585978274 381.01518106982 94.45754072181539 C 393.716405988484 93.3912948858816 400.067018447816 92.84215976493927 412.76824336648 91.7657305184516 C 425.469468285144 90.68930127196396 431.82008074447606 90.15588999524702 444.52130566314 89.07539448937708 C 457.22109281579594 87.99502129452202 463.570986392124 87.43993732151209 476.27077354478 86.36355876663913 C 488.97199846344404 85.28705835299175 495.32261092277605 84.73892334721175 508.02383584144 83.6931970680762 C 520.723622994096 82.64758916411371 527.073516570424 82.15994176531119 539.77330372308 81.13522330889404 C 552.474528641748 80.11038884223586 558.825141101082 79.59872555599586 571.52636601975 78.5693147603879 C 584.2261531724059 77.54002049305684 590.576046748734 77.01097860881644 603.27583390139 75.98846065154652 C 615.977058820054 74.9658269331584 622.3276712793861 74.45065909912064 635.02889619805 73.45643557124278 C 647.728683350706 72.46232458847783 654.078576927034 71.98356890175667 666.77836407969 71.01762437493947 C 679.4795889983541 70.05157049178509 685.830201457686 69.54807483481947 698.53142637635 68.62643954631382 C 711.231213529006 67.7049085860047 717.581107105334 67.27640078977346 730.28089425799 66.40970875290253 C 742.9821191766539 65.54291859624935 749.332731635986 65.13470060864074 762.03395655465 64.29273406250354 C 774.733743707306 63.4508628261406 781.0836372836341 63.01014882245455 793.78342443629 62.200114296652146 C 806.4846493549579 61.38998806536714 812.835261814292 61.00716216098411 825.53648673296 60.242332169785016 C 838.236273885616 59.47758875657926 844.586167461944 59.08954155120895 857.2859546146 58.37618078564003 C 869.987179533264 57.66273925920103 876.3377919925961 57.33887015089095 889.03901691126 56.675326439765215 C 901.740241829924 56.01178272863948 920.79207920792 55.05846223001137 920.79207920792 55.05846223001137"
                                  class="highcharts-graph" data-z-index="1" stroke="#7cb5ec"
                                  stroke-width="2" stroke-linejoin="round"
                                  stroke-linecap="round"></path>
                            <path fill="none"
                                  d="M -10 144.76749185358975 L 0 144.76749185358975 C 0 144.76749185358975 19.051837377997202 128.47712610308812 31.753062296662 123.08666396164986 C 44.4528494493184 117.6962018202116 50.8027430256466 118.2428301544742 63.502530178303 117.6962018202116 C 76.2037550969678 117.14957348594899 82.5543675563002 117.6962018202116 95.255592474965 117.14957348594899 C 107.955379627623 116.60294515168638 114.305273203952 115.29835820652448 127.00506035661 114.3145286438774 C 139.706285275274 113.3305877000958 146.056897734606 113.14209185155629 158.75812265327 112.23014721987732 C 171.45790980592602 111.31830581942219 177.807803382254 110.73824574650388 190.50759053491 109.75506356354214 C 203.208815453574 108.77177007273679 209.559427912906 108.29848889749503 222.26065283157 107.31395803545954 C 234.960439984226 106.32953862133684 241.310333560554 105.84202729771715 254.01012071321 104.83268787314663 C 266.711345631874 103.82323417942358 273.061958091206 103.29641313701507 285.76318300987 102.26697523972558 C 298.462970162526 101.23765387378056 304.812863738854 100.71979464157498 317.51265089151 99.68578971506035 C 330.21387581017797 98.65166772696652 336.564488269512 98.14236693846131 349.26571318818 97.09665795320446 C 361.965500340836 96.05106734116333 368.315393917164 95.52366585978274 381.01518106982 94.45754072181539 C 393.716405988484 93.3912948858816 400.067018447816 92.84215976493927 412.76824336648 91.7657305184516 C 425.469468285144 90.68930127196396 431.82008074447606 90.15588999524702 444.52130566314 89.07539448937708 C 457.22109281579594 87.99502129452202 463.570986392124 87.43993732151209 476.27077354478 86.36355876663913 C 488.97199846344404 85.28705835299175 495.32261092277605 84.73892334721175 508.02383584144 83.6931970680762 C 520.723622994096 82.64758916411371 527.073516570424 82.15994176531119 539.77330372308 81.13522330889404 C 552.474528641748 80.11038884223586 558.825141101082 79.59872555599586 571.52636601975 78.5693147603879 C 584.2261531724059 77.54002049305684 590.576046748734 77.01097860881644 603.27583390139 75.98846065154652 C 615.977058820054 74.9658269331584 622.3276712793861 74.45065909912064 635.02889619805 73.45643557124278 C 647.728683350706 72.46232458847783 654.078576927034 71.98356890175667 666.77836407969 71.01762437493947 C 679.4795889983541 70.05157049178509 685.830201457686 69.54807483481947 698.53142637635 68.62643954631382 C 711.231213529006 67.7049085860047 717.581107105334 67.27640078977346 730.28089425799 66.40970875290253 C 742.9821191766539 65.54291859624935 749.332731635986 65.13470060864074 762.03395655465 64.29273406250354 C 774.733743707306 63.4508628261406 781.0836372836341 63.01014882245455 793.78342443629 62.200114296652146 C 806.4846493549579 61.38998806536714 812.835261814292 61.00716216098411 825.53648673296 60.242332169785016 C 838.236273885616 59.47758875657926 844.586167461944 59.08954155120895 857.2859546146 58.37618078564003 C 869.987179533264 57.66273925920103 876.3377919925961 57.33887015089095 889.03901691126 56.675326439765215 C 901.740241829924 56.01178272863948 920.79207920792 55.05846223001137 920.79207920792 55.05846223001137 L 930.79207920792 55.05846223001137"
                                  stroke-linejoin="round" stroke="rgba(192,192,192,0.0001)"
                                  stroke-width="22" visibility="visible" data-z-index="2"
                                  class="highcharts-tracker-line"></path>
                        </g>
                        <g data-z-index="0.1"
                           class="highcharts-markers highcharts-series-0 highcharts-spline-series highcharts-color-0 highcharts-tracker"
                           transform="translate(70,10) scale(1 1)"></g>
                    </g>
                    <text x="505" text-anchor="middle" class="highcharts-title" data-z-index="4"
                          style="color:#333333;font-size:18px;fill:#333333;" y="24"></text>
                    <text x="505" text-anchor="middle" class="highcharts-subtitle"
                          data-z-index="4" style="color:#666666;fill:#666666;" y="24"></text>
                    <g class="highcharts-axis-labels highcharts-xaxis-labels "
                       data-z-index="7"></g>
                    <g class="highcharts-axis-labels highcharts-yaxis-labels " data-z-index="7">
                        <text x="55"
                              style="color:#666666;cursor:default;font-size:11px;fill:#666666;"
                              text-anchor="end" transform="translate(0,0)" y="180" opacity="1">0
                        </text>
                        <text x="55"
                              style="color:#666666;cursor:default;font-size:11px;fill:#666666;"
                              text-anchor="end" transform="translate(0,0)" y="125" opacity="1">
                            100
                        </text>
                        <text x="55"
                              style="color:#666666;cursor:default;font-size:11px;fill:#666666;"
                              text-anchor="end" transform="translate(0,0)" y="70" opacity="1">
                            200
                        </text>
                        <text x="55"
                              style="color:#666666;cursor:default;font-size:11px;fill:#666666;"
                              text-anchor="end" transform="translate(0,0)" y="15" opacity="1">
                            300
                        </text>
                    </g>
                    <g class="highcharts-axis-labels highcharts-yaxis-labels "
                       data-z-index="7"></g>
                </svg>
            </div>
            <div class="svg-wrap">
                <svg version="1.1" class="highcharts-root"
                     style="font-family:Lucida Grande, Lucida Sans Unicode, Arial, Helvetica, sans-serif;font-size:12px;"
                     xmlns="http://www.w3.org/2000/svg" width="1116" height="400"
                     viewBox="0 0 1116 400">
                    <desc>Created with Highcharts 6.2.0</desc>
                    <defs>
                        <clipPath id="highcharts-6mh5h5f-1985">
                            <rect x="0" y="0" width="971" height="365" fill="none"></rect>
                        </clipPath>
                    </defs>
                    <rect fill="#ffffff" class="highcharts-background" x="0" y="0" width="1116"
                          height="400" rx="0" ry="0"></rect>
                    <rect fill="none" class="highcharts-plot-background" x="70" y="10"
                          width="971" height="365"></rect>
                    <g class="highcharts-grid highcharts-xaxis-grid " data-z-index="1">
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 69.5 10 L 69.5 375"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 159.5 10 L 159.5 375"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 249.5 10 L 249.5 375"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 339.5 10 L 339.5 375"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 430.5 10 L 430.5 375"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 520.5 10 L 520.5 375"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 610.5 10 L 610.5 375"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 700.5 10 L 700.5 375"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 790.5 10 L 790.5 375"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 880.5 10 L 880.5 375"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 971.5 10 L 971.5 375"
                              opacity="1"></path>
                    </g>
                    <g class="highcharts-grid highcharts-yaxis-grid " data-z-index="1">
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 70 375.5 L 1041 375.5"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 70 329.5 L 1041 329.5"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 70 284.5 L 1041 284.5"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 70 238.5 L 1041 238.5"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 70 193.5 L 1041 193.5"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 70 147.5 L 1041 147.5"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 70 101.5 L 1041 101.5"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 70 56.5 L 1041 56.5"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 70 9.5 L 1041 9.5"
                              opacity="1"></path>
                    </g>
                    <g class="highcharts-grid highcharts-yaxis-grid " data-z-index="1"></g>
                    <g class="highcharts-grid highcharts-yaxis-grid " data-z-index="1">
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 70 375.5 L 1041 375.5"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 70 132.5 L 1041 132.5"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 70 314.5 L 1041 314.5"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 70 253.5 L 1041 253.5"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 70 193.5 L 1041 193.5"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 70 71.5 L 1041 71.5"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 70 9.5 L 1041 9.5"
                              opacity="1"></path>
                    </g>
                    <g class="highcharts-grid highcharts-yaxis-grid " data-z-index="1"></g>
                    <g class="highcharts-grid highcharts-yaxis-grid " data-z-index="1"></g>
                    <rect fill="none" class="highcharts-plot-border" data-z-index="1" x="70"
                          y="10" width="971" height="365"></rect>
                    <g class="highcharts-axis highcharts-xaxis " data-z-index="2">
                        <path fill="none" class="highcharts-tick" stroke="#ccd6eb"
                              stroke-width="1" d="M 69.5 375 L 69.5 385" opacity="1"></path>
                        <path fill="none" class="highcharts-tick" stroke="#ccd6eb"
                              stroke-width="1" d="M 159.5 375 L 159.5 385" opacity="1"></path>
                        <path fill="none" class="highcharts-tick" stroke="#ccd6eb"
                              stroke-width="1" d="M 249.5 375 L 249.5 385" opacity="1"></path>
                        <path fill="none" class="highcharts-tick" stroke="#ccd6eb"
                              stroke-width="1" d="M 339.5 375 L 339.5 385" opacity="1"></path>
                        <path fill="none" class="highcharts-tick" stroke="#ccd6eb"
                              stroke-width="1" d="M 430.5 375 L 430.5 385" opacity="1"></path>
                        <path fill="none" class="highcharts-tick" stroke="#ccd6eb"
                              stroke-width="1" d="M 520.5 375 L 520.5 385" opacity="1"></path>
                        <path fill="none" class="highcharts-tick" stroke="#ccd6eb"
                              stroke-width="1" d="M 610.5 375 L 610.5 385" opacity="1"></path>
                        <path fill="none" class="highcharts-tick" stroke="#ccd6eb"
                              stroke-width="1" d="M 700.5 375 L 700.5 385" opacity="1"></path>
                        <path fill="none" class="highcharts-tick" stroke="#ccd6eb"
                              stroke-width="1" d="M 790.5 375 L 790.5 385" opacity="1"></path>
                        <path fill="none" class="highcharts-tick" stroke="#ccd6eb"
                              stroke-width="1" d="M 880.5 375 L 880.5 385" opacity="1"></path>
                        <path fill="none" class="highcharts-tick" stroke="#ccd6eb"
                              stroke-width="1" d="M 971.5 375 L 971.5 385" opacity="1"></path>
                        <path fill="none" class="highcharts-axis-line" stroke="#ccd6eb"
                              stroke-width="1" data-z-index="7"
                              d="M 70 375.5 L 1041 375.5"></path>
                    </g>
                    <g class="highcharts-axis highcharts-yaxis " data-z-index="2">
                        <text x="23.015625" data-z-index="7" text-anchor="middle"
                              transform="translate(0,0) rotate(270 23.015625 192.5)"
                              class="highcharts-axis-title" style="color:#666666;fill:#666666;"
                              y="192.5">
                            <tspan>Head - ft</tspan>
                        </text>
                        <path fill="none" class="highcharts-axis-line" data-z-index="7"
                              d="M 70 10 L 70 375"></path>
                    </g>
                    <g class="highcharts-axis highcharts-yaxis " data-z-index="2">
                        <text x="1051" data-z-index="7" text-anchor="middle"
                              transform="translate(0,0) rotate(90 1051 192.5)"
                              class="highcharts-axis-title" style="color:#666666;fill:#666666;"
                              y="192.5">
                            <tspan>Efficiency %</tspan>
                        </text>
                        <path fill="none" class="highcharts-axis-line" stroke="#ccd6eb"
                              stroke-width="1" data-z-index="7"
                              d="M 1041.5 10 L 1041.5 375"></path>
                    </g>
                    <g class="highcharts-axis highcharts-yaxis " data-z-index="2">
                        <path fill="none" class="highcharts-axis-line" data-z-index="7"
                              d="M 1065 10 L 1065 375"></path>
                    </g>
                    <g class="highcharts-axis highcharts-yaxis " data-z-index="2">
                        <path fill="none" class="highcharts-axis-line" data-z-index="7"
                              d="M 1106 10 L 1106 375"></path>
                    </g>
                    <g class="highcharts-axis highcharts-yaxis " data-z-index="2">
                        <path fill="none" class="highcharts-axis-line" data-z-index="7"
                              d="M 1106 10 L 1106 375"></path>
                    </g>
                    <g class="highcharts-series-group" data-z-index="3">
                        <g data-z-index="0.1"
                           class="highcharts-series highcharts-series-0 highcharts-spline-series "
                           transform="translate(70,10) scale(1 1)"
                           clip-path="url(#highcharts-6mh5h5f-1985)">
                            <path fill="none"
                                  d="M 0 16.904724594987727 C 0 16.904724594987727 19.8904492607544 16.421227949654224 33.150748767924 16.421227949654224 C 46.4110482750932 16.421227949654224 53.04119802867781 16.65789904828049 66.301497535847 16.75006008174182 C 79.5617970430166 16.842221115203156 86.1919467966014 16.80718435796472 99.452246303771 16.882033116960883 C 112.7139882453466 16.956890017886657 119.34485921613441 16.899632201605606 132.60660115771 17.124324231546666 C 145.866900664882 17.34899182250259 152.497050418468 17.67052405077241 165.75734992564 18.005432169203345 C 179.017649432808 18.340340287634177 185.647799186392 18.329298270102402 198.90809869356 18.79886482370108 C 212.168398200728 19.268431377299763 218.79854795431203 19.714908760628514 232.05884746148 20.35326493719674 C 245.319146968652 20.99162111376516 251.94929672223802 21.3233552731331 265.20959622941 21.990645706542693 C 278.469895736578 22.657936139952085 285.100045490162 22.88150629902967 298.36034499733 23.68971710424421 C 311.62064450450197 24.497927909458994 318.250794258088 24.991784560243513 331.51109376526 26.031699732616005 C 344.77283570683596 27.071728025315906 351.403706677624 27.76035091381759 364.6654486192 28.88957576692519 C 377.9257481263679 30.01867779809961 384.555897879952 30.417982333114104 397.81619738712 31.677516943321052 C 411.076496894292 32.937051553528384 417.706646647878 33.69864178872074 430.96694615505 35.18724881796089 C 444.22724566221797 36.675855847200594 450.857395415802 37.5008101441869 464.11769492297 39.120552089520686 C 477.377994430138 40.740294034854486 484.00814418372204 41.52687338200739 497.26844369089 43.285958544629864 C 510.528743198062 45.045043707252866 517.1588929516481 45.916969443756564 530.41919245882 47.91597790263438 C 543.6794919659881 49.91498636151162 550.309641719572 51.00221134013895 563.56994122674 53.28100083901751 C 576.831683168316 55.56003822101365 583.462554139104 56.88328161838885 596.72429608068 59.31054510482113 C 609.984595587852 61.73754458608909 616.614745341438 62.865343660295295 629.87504484861 65.41665825826811 C 643.135344355778 67.9679728562402 649.7654941093621 69.27119638117874 663.02579361653 72.0671180946834 C 676.286093123698 74.86303980818806 682.9162428772821 76.36388452547419 696.17654238445 79.39626682579143 C 709.4368418916221 82.4286491261096 716.066991645208 83.98418203938404 729.32729115238 87.22902959627191 C 742.587590659548 90.47387715315881 749.217740413132 92.15924452188898 762.4780399203 95.62050461022835 C 775.7383394274681 99.08176469856772 782.3684891810519 100.85372374376443 795.62878868822 104.53533003796878 C 808.8905306298 108.21733681148409 815.52140160059 110.10722695644235 828.78314354217 114.02953727952749 C 842.0434430493381 117.95142098630465 848.673592802922 119.98470997287545 861.93389231009 124.14581511262458 C 875.1941918172579 128.3069202523737 881.8243415708421 130.43261705026373 895.08464107801 134.83506297827302 C 908.3449405851819 139.23750890628364 914.9750903387679 141.51683178164177 928.23538984594 146.15804475267436 C 941.495689353108 150.79925772370558 961.38613861386 158.04112783343254 961.38613861386 158.04112783343254"
                                  class="highcharts-graph" data-z-index="1" stroke="black"
                                  stroke-width="2" stroke-linejoin="round"
                                  stroke-linecap="round"></path>
                            <path fill="none"
                                  d="M -10 16.904724594987727 L 0 16.904724594987727 C 0 16.904724594987727 19.8904492607544 16.421227949654224 33.150748767924 16.421227949654224 C 46.4110482750932 16.421227949654224 53.04119802867781 16.65789904828049 66.301497535847 16.75006008174182 C 79.5617970430166 16.842221115203156 86.1919467966014 16.80718435796472 99.452246303771 16.882033116960883 C 112.7139882453466 16.956890017886657 119.34485921613441 16.899632201605606 132.60660115771 17.124324231546666 C 145.866900664882 17.34899182250259 152.497050418468 17.67052405077241 165.75734992564 18.005432169203345 C 179.017649432808 18.340340287634177 185.647799186392 18.329298270102402 198.90809869356 18.79886482370108 C 212.168398200728 19.268431377299763 218.79854795431203 19.714908760628514 232.05884746148 20.35326493719674 C 245.319146968652 20.99162111376516 251.94929672223802 21.3233552731331 265.20959622941 21.990645706542693 C 278.469895736578 22.657936139952085 285.100045490162 22.88150629902967 298.36034499733 23.68971710424421 C 311.62064450450197 24.497927909458994 318.250794258088 24.991784560243513 331.51109376526 26.031699732616005 C 344.77283570683596 27.071728025315906 351.403706677624 27.76035091381759 364.6654486192 28.88957576692519 C 377.9257481263679 30.01867779809961 384.555897879952 30.417982333114104 397.81619738712 31.677516943321052 C 411.076496894292 32.937051553528384 417.706646647878 33.69864178872074 430.96694615505 35.18724881796089 C 444.22724566221797 36.675855847200594 450.857395415802 37.5008101441869 464.11769492297 39.120552089520686 C 477.377994430138 40.740294034854486 484.00814418372204 41.52687338200739 497.26844369089 43.285958544629864 C 510.528743198062 45.045043707252866 517.1588929516481 45.916969443756564 530.41919245882 47.91597790263438 C 543.6794919659881 49.91498636151162 550.309641719572 51.00221134013895 563.56994122674 53.28100083901751 C 576.831683168316 55.56003822101365 583.462554139104 56.88328161838885 596.72429608068 59.31054510482113 C 609.984595587852 61.73754458608909 616.614745341438 62.865343660295295 629.87504484861 65.41665825826811 C 643.135344355778 67.9679728562402 649.7654941093621 69.27119638117874 663.02579361653 72.0671180946834 C 676.286093123698 74.86303980818806 682.9162428772821 76.36388452547419 696.17654238445 79.39626682579143 C 709.4368418916221 82.4286491261096 716.066991645208 83.98418203938404 729.32729115238 87.22902959627191 C 742.587590659548 90.47387715315881 749.217740413132 92.15924452188898 762.4780399203 95.62050461022835 C 775.7383394274681 99.08176469856772 782.3684891810519 100.85372374376443 795.62878868822 104.53533003796878 C 808.8905306298 108.21733681148409 815.52140160059 110.10722695644235 828.78314354217 114.02953727952749 C 842.0434430493381 117.95142098630465 848.673592802922 119.98470997287545 861.93389231009 124.14581511262458 C 875.1941918172579 128.3069202523737 881.8243415708421 130.43261705026373 895.08464107801 134.83506297827302 C 908.3449405851819 139.23750890628364 914.9750903387679 141.51683178164177 928.23538984594 146.15804475267436 C 941.495689353108 150.79925772370558 961.38613861386 158.04112783343254 961.38613861386 158.04112783343254 L 971.38613861386 158.04112783343254"
                                  stroke-linejoin="round" stroke="rgba(192,192,192,0.0001)"
                                  stroke-width="22" visibility="visible" data-z-index="2"
                                  class="highcharts-tracker-line"></path>
                        </g>
                        <g data-z-index="0.1"
                           class="highcharts-markers highcharts-series-0 highcharts-spline-series  highcharts-tracker"
                           transform="translate(70,10) scale(1 1)"></g>
                        <g data-z-index="0.1"
                           class="highcharts-series highcharts-series-1 highcharts-spline-series "
                           transform="translate(70,10) scale(1 1)"
                           clip-path="url(#highcharts-6mh5h5f-1985)">
                            <path fill="none"
                                  d="M 0 55.78433017358901 C 0 55.78433017358901 19.1136983323728 55.3888436102788 31.856163887288 55.3888436102788 C 44.5971870077956 55.3888436102788 50.9676985680494 55.56582921372388 63.708721688557 55.64893096744299 C 76.45118724347219 55.73204212926283 82.8224200209298 55.71636603578949 95.564885575845 55.80437589912617 C 108.305908696351 55.89237579983398 114.676420256604 55.86776773958907 127.41744337711 56.088955377554214 C 140.159908932026 56.310168056574305 146.53114170948402 56.58366893982341 159.2736072644 56.91037669158925 C 172.014630384908 57.237047460363016 178.38514194516202 57.26898446445267 191.12616506567 57.722401678903225 C 203.868630620586 58.17587022554156 210.239863398044 58.567833999698564 222.98232895296 59.17759109431148 C 235.723352073468 59.787279165028664 242.093863633722 60.11208575970241 254.83488675423 60.77101459222848 C 267.577352309146 61.43001802328652 273.948585086604 61.679560693221916 286.69105064152 62.47242175327176 C 299.432073762028 63.265193062239376 305.80258532228197 63.73322205496035 318.54360844279 64.73509551477213 C 331.286073997702 65.73708239850073 337.657306775158 66.37788695976329 350.39977233007 67.48207261212269 C 363.140795450578 68.5861332717665 369.511307010832 69.01858415844288 382.25233013134 70.25571129478016 C 394.994795686256 71.49297848853134 401.366028463714 72.2207231735291 414.10849401863 73.66805843734386 C 426.850959573546 75.11539370115861 433.222192351004 75.90862668587096 445.96465790592 77.49238761385396 C 458.705681026428 79.07596926167751 465.076192586682 79.8578411794345 477.81721570719 81.58641487686026 C 490.559681262106 83.31518426925922 496.93091403956396 84.18273637533397 509.67337959448 86.13574533841575 C 522.414402714988 88.08853322282827 528.784914275242 89.14272425355006 541.52593739575 91.350906995596 C 554.268402950662 93.55933973002696 560.639635728118 94.81283364650271 573.38210128303 97.17728402960802 C 586.123124403538 99.54146675928592 592.493635963792 100.67050546697115 605.2346590843 103.17248977755406 C 617.977124639216 105.6747573423328 624.3483574166739 106.95567255859036 637.09082297159 109.68791371801211 C 649.831846092098 112.41984559045619 656.2023576523519 113.87223204151638 668.94338077286 116.83292235721868 C 681.6858463277761 119.79394785805817 688.0570791052339 121.32016257405654 700.79954466015 124.49220325936662 C 713.5405677806581 127.6638848728308 719.911079340912 129.31154177851383 732.65210246142 132.69222810415428 C 745.394568016336 136.07329716344438 751.765800793794 137.79707839803558 764.50826634871 141.39659172169297 C 777.249289469218 144.99569758402762 783.619801029472 146.851941370361 796.36082414998 150.68877606913432 C 809.103289704892 154.52604514294325 815.474522482348 156.51137486552912 828.21698803726 160.58185115314856 C 840.9580111577679 164.65186666690812 847.328522718022 166.73110430513333 860.06954583853 171.04000557258183 C 872.8120113934459 175.34939465858224 879.1832441709039 177.58083033564742 891.92570972582 182.1275770367709 C 904.6681752807359 186.67432373789433 923.78187361311 193.77373907819916 923.78187361311 193.77373907819916"
                                  class="highcharts-graph" data-z-index="1" stroke="#24CBE5"
                                  stroke-width="2" stroke-linejoin="round"
                                  stroke-linecap="round"></path>
                            <path fill="none"
                                  d="M -10 55.78433017358901 L 0 55.78433017358901 C 0 55.78433017358901 19.1136983323728 55.3888436102788 31.856163887288 55.3888436102788 C 44.5971870077956 55.3888436102788 50.9676985680494 55.56582921372388 63.708721688557 55.64893096744299 C 76.45118724347219 55.73204212926283 82.8224200209298 55.71636603578949 95.564885575845 55.80437589912617 C 108.305908696351 55.89237579983398 114.676420256604 55.86776773958907 127.41744337711 56.088955377554214 C 140.159908932026 56.310168056574305 146.53114170948402 56.58366893982341 159.2736072644 56.91037669158925 C 172.014630384908 57.237047460363016 178.38514194516202 57.26898446445267 191.12616506567 57.722401678903225 C 203.868630620586 58.17587022554156 210.239863398044 58.567833999698564 222.98232895296 59.17759109431148 C 235.723352073468 59.787279165028664 242.093863633722 60.11208575970241 254.83488675423 60.77101459222848 C 267.577352309146 61.43001802328652 273.948585086604 61.679560693221916 286.69105064152 62.47242175327176 C 299.432073762028 63.265193062239376 305.80258532228197 63.73322205496035 318.54360844279 64.73509551477213 C 331.286073997702 65.73708239850073 337.657306775158 66.37788695976329 350.39977233007 67.48207261212269 C 363.140795450578 68.5861332717665 369.511307010832 69.01858415844288 382.25233013134 70.25571129478016 C 394.994795686256 71.49297848853134 401.366028463714 72.2207231735291 414.10849401863 73.66805843734386 C 426.850959573546 75.11539370115861 433.222192351004 75.90862668587096 445.96465790592 77.49238761385396 C 458.705681026428 79.07596926167751 465.076192586682 79.8578411794345 477.81721570719 81.58641487686026 C 490.559681262106 83.31518426925922 496.93091403956396 84.18273637533397 509.67337959448 86.13574533841575 C 522.414402714988 88.08853322282827 528.784914275242 89.14272425355006 541.52593739575 91.350906995596 C 554.268402950662 93.55933973002696 560.639635728118 94.81283364650271 573.38210128303 97.17728402960802 C 586.123124403538 99.54146675928592 592.493635963792 100.67050546697115 605.2346590843 103.17248977755406 C 617.977124639216 105.6747573423328 624.3483574166739 106.95567255859036 637.09082297159 109.68791371801211 C 649.831846092098 112.41984559045619 656.2023576523519 113.87223204151638 668.94338077286 116.83292235721868 C 681.6858463277761 119.79394785805817 688.0570791052339 121.32016257405654 700.79954466015 124.49220325936662 C 713.5405677806581 127.6638848728308 719.911079340912 129.31154177851383 732.65210246142 132.69222810415428 C 745.394568016336 136.07329716344438 751.765800793794 137.79707839803558 764.50826634871 141.39659172169297 C 777.249289469218 144.99569758402762 783.619801029472 146.851941370361 796.36082414998 150.68877606913432 C 809.103289704892 154.52604514294325 815.474522482348 156.51137486552912 828.21698803726 160.58185115314856 C 840.9580111577679 164.65186666690812 847.328522718022 166.73110430513333 860.06954583853 171.04000557258183 C 872.8120113934459 175.34939465858224 879.1832441709039 177.58083033564742 891.92570972582 182.1275770367709 C 904.6681752807359 186.67432373789433 923.78187361311 193.77373907819916 923.78187361311 193.77373907819916 L 933.78187361311 193.77373907819916"
                                  stroke-linejoin="round" stroke="rgba(192,192,192,0.0001)"
                                  stroke-width="22" visibility="visible" data-z-index="2"
                                  class="highcharts-tracker-line"></path>
                        </g>
                        <g data-z-index="0.1"
                           class="highcharts-markers highcharts-series-1 highcharts-spline-series  highcharts-tracker"
                           transform="translate(70,10) scale(1 1)"></g>
                        <g data-z-index="0.1"
                           class="highcharts-series highcharts-series-2 highcharts-spline-series "
                           transform="translate(70,10) scale(1 1)"
                           clip-path="url(#highcharts-6mh5h5f-1985)">
                            <path fill="none"
                                  d="M 0 212.2646669470343 C 0 212.2646669470343 15.6345465417396 212.17543358772798 26.057577569566 212.17543358772798 C 36.48060859739199 212.17543358772798 41.692124111305 212.17543358772798 52.115155139131 212.19957737111088 C 62.538186166957395 212.22372115449377 67.7497016808706 212.29534509906364 78.172732708697 212.4192609371524 C 88.5957637365222 212.5431767752411 93.8072792504348 212.62383080963198 104.23031027826 212.81915656155462 C 114.65334130608801 213.0144823134773 119.864856820002 213.1172476467008 130.28788784783 213.39588969676566 C 140.710918875654 213.6745317468304 145.922434389566 213.84059356871816 156.34546541739 214.21236681187872 C 166.76849644521798 214.58414005503946 171.98001195913199 214.7770149570616 182.40304298696 215.25475591256892 C 192.827516449192 215.732562982241 198.03975318030803 216.01321512873696 208.46422664254 216.6012368748273 C 218.88725767036803 217.18917725634802 224.09877318428198 217.50445548826943 234.52180421211 218.1946612315966 C 244.94483523993398 218.88486697492348 250.15635075384597 219.23903262626877 260.57938178167 220.05226559146237 C 271.002412809498 220.8654985566563 276.213928323412 221.31165165498945 286.63695935124 222.26082605756545 C 297.05999037906804 223.21000046014146 302.27150589298196 223.7169261814997 312.69453692081 224.79813760434234 C 323.117567948634 225.8793490271846 328.329083462546 226.45029362447914 338.75211449037 227.66688317177778 C 349.175145518198 228.88347271907688 354.386661032112 229.5221016163931 364.80969205994 230.8810853408368 C 375.232723087764 232.24006906527998 380.444238601676 232.95134349606164 390.8672696295 234.46180179399502 C 401.290300657328 235.97226009192897 406.501816171242 236.7648974015686 416.92484719907 238.43337683050515 C 427.34787822689395 240.10185625944106 432.559393740806 240.97625163830514 442.98242476863 242.80419893867617 C 453.40545579645806 244.63214623904793 458.616971310372 245.57812181317036 469.0400023382 247.57311333236208 C 479.46303336602807 249.5681048515538 484.674548879942 250.61665934326103 495.09757990777 252.77915653463486 C 505.52061093559405 254.94165372600787 510.732126449506 256.0582334918197 521.15515747733 258.38559928922916 C 531.578188505158 260.71296508663954 536.789704019072 261.9043947729788 547.2127350469 264.41598552168443 C 557.6372085091319 266.9279238472988 562.8494452402481 268.24632650361934 573.27391870248 270.9444219750293 C 583.696949730308 273.64214411096594 588.9084652442219 275.04234702616526 599.33149627205 277.90552954005096 C 609.7545272998739 280.76871205393553 614.9660428137861 282.208708019911 625.38907384161 285.2603345444551 C 635.812104869438 288.31196106900035 641.023620383352 289.9087630914804 651.44665141118 293.1636621627743 C 661.869682439004 296.4185612340669 667.081197952916 298.09247914417506 677.50422898074 301.5348299009213 C 687.927260008568 304.9771806576689 693.1387755224821 306.73284339308333 703.56180655031 310.37541594650895 C 713.9848375781341 314.0179884999332 719.196353092046 315.9053091735226 729.61938411987 319.74769266804606 C 740.042415147698 323.590076162571 755.67696168944 329.58733341912983 755.67696168944 329.58733341912983"
                                  class="highcharts-graph" data-z-index="1" stroke="black"
                                  stroke-width="2" stroke-linejoin="round"
                                  stroke-linecap="round"></path>
                            <path fill="none"
                                  d="M -10 212.2646669470343 L 0 212.2646669470343 C 0 212.2646669470343 15.6345465417396 212.17543358772798 26.057577569566 212.17543358772798 C 36.48060859739199 212.17543358772798 41.692124111305 212.17543358772798 52.115155139131 212.19957737111088 C 62.538186166957395 212.22372115449377 67.7497016808706 212.29534509906364 78.172732708697 212.4192609371524 C 88.5957637365222 212.5431767752411 93.8072792504348 212.62383080963198 104.23031027826 212.81915656155462 C 114.65334130608801 213.0144823134773 119.864856820002 213.1172476467008 130.28788784783 213.39588969676566 C 140.710918875654 213.6745317468304 145.922434389566 213.84059356871816 156.34546541739 214.21236681187872 C 166.76849644521798 214.58414005503946 171.98001195913199 214.7770149570616 182.40304298696 215.25475591256892 C 192.827516449192 215.732562982241 198.03975318030803 216.01321512873696 208.46422664254 216.6012368748273 C 218.88725767036803 217.18917725634802 224.09877318428198 217.50445548826943 234.52180421211 218.1946612315966 C 244.94483523993398 218.88486697492348 250.15635075384597 219.23903262626877 260.57938178167 220.05226559146237 C 271.002412809498 220.8654985566563 276.213928323412 221.31165165498945 286.63695935124 222.26082605756545 C 297.05999037906804 223.21000046014146 302.27150589298196 223.7169261814997 312.69453692081 224.79813760434234 C 323.117567948634 225.8793490271846 328.329083462546 226.45029362447914 338.75211449037 227.66688317177778 C 349.175145518198 228.88347271907688 354.386661032112 229.5221016163931 364.80969205994 230.8810853408368 C 375.232723087764 232.24006906527998 380.444238601676 232.95134349606164 390.8672696295 234.46180179399502 C 401.290300657328 235.97226009192897 406.501816171242 236.7648974015686 416.92484719907 238.43337683050515 C 427.34787822689395 240.10185625944106 432.559393740806 240.97625163830514 442.98242476863 242.80419893867617 C 453.40545579645806 244.63214623904793 458.616971310372 245.57812181317036 469.0400023382 247.57311333236208 C 479.46303336602807 249.5681048515538 484.674548879942 250.61665934326103 495.09757990777 252.77915653463486 C 505.52061093559405 254.94165372600787 510.732126449506 256.0582334918197 521.15515747733 258.38559928922916 C 531.578188505158 260.71296508663954 536.789704019072 261.9043947729788 547.2127350469 264.41598552168443 C 557.6372085091319 266.9279238472988 562.8494452402481 268.24632650361934 573.27391870248 270.9444219750293 C 583.696949730308 273.64214411096594 588.9084652442219 275.04234702616526 599.33149627205 277.90552954005096 C 609.7545272998739 280.76871205393553 614.9660428137861 282.208708019911 625.38907384161 285.2603345444551 C 635.812104869438 288.31196106900035 641.023620383352 289.9087630914804 651.44665141118 293.1636621627743 C 661.869682439004 296.4185612340669 667.081197952916 298.09247914417506 677.50422898074 301.5348299009213 C 687.927260008568 304.9771806576689 693.1387755224821 306.73284339308333 703.56180655031 310.37541594650895 C 713.9848375781341 314.0179884999332 719.196353092046 315.9053091735226 729.61938411987 319.74769266804606 C 740.042415147698 323.590076162571 755.67696168944 329.58733341912983 755.67696168944 329.58733341912983 L 765.67696168944 329.58733341912983"
                                  stroke-linejoin="round" stroke="rgba(192,192,192,0.0001)"
                                  stroke-width="22" visibility="visible" data-z-index="2"
                                  class="highcharts-tracker-line"></path>
                        </g>
                        <g data-z-index="0.1"
                           class="highcharts-markers highcharts-series-2 highcharts-spline-series  highcharts-tracker"
                           transform="translate(70,10) scale(1 1)"></g>
                        <g data-z-index="0.1"
                           class="highcharts-series highcharts-series-3 highcharts-scatter-series  highcharts-tracker"
                           transform="translate(70,10) scale(1 1)"
                           clip-path="url(#highcharts-6mh5h5f-1985)"></g>
                        <g data-z-index="0.1"
                           class="highcharts-markers highcharts-series-3 highcharts-scatter-series  highcharts-tracker"
                           transform="translate(70,10) scale(1 1)">
                            <image preserveAspectRatio="none"
                                   xlink:href="https://wiseselector.flopo.com.br/images/point.png"
                                   x="540" y="91.25" width="20" transform="translate(-10,-10)"
                                   height="20" fill="black" class="highcharts-point"></image>
                        </g>
                        <g data-z-index="0.1"
                           class="highcharts-series highcharts-series-4 highcharts-spline-series "
                           transform="translate(70,10) scale(1 1)"
                           clip-path="url(#highcharts-6mh5h5f-1985)">
                            <path fill="none"
                                  d="M 0 365 C 0 365 19.1136983323728 340.1946427323053 31.856163887288 326.5866833534227 C 44.5971870077956 312.9802643819865 50.9676985680494 309.45192430132624 63.708721688557 296.964054124203 C 76.45118724347219 284.4747701725775 82.8224200209298 275.91322063859866 95.564885575845 264.14379803155083 C 108.305908696351 252.37570771141964 114.676420256604 248.36453561598378 127.41744337711 238.12027180625546 C 140.159908932026 227.8748482247816 146.53114170948402 222.35051985497907 159.2736072644 212.91957955354542 C 172.014630384908 203.48970682515966 178.38514194516202 199.3251613424624 191.12616506567 190.9682392317069 C 203.868630620586 182.61037101859495 210.239863398044 178.6731672323085 222.98232895296 171.1326037438768 C 235.723352073468 163.59289383972083 242.093863633722 160.02535925542986 254.83488675423 153.2675557502377 C 267.577352309146 146.50898718181583 273.948585086604 143.36026241206778 286.69105064152 137.3416735598417 C 299.432073762028 131.32376600587858 305.80258532228197 128.5258357669175 318.54360844279 123.17631473476473 C 331.286073997702 117.8261880736049 337.657306775158 115.34981653039299 350.39977233007 110.59255432656016 C 363.140795450578 105.83583064006858 369.511307010832 103.54654957737199 382.25233013134 99.39135000895374 C 394.994795686256 95.23568002283251 401.366028463714 93.40254792698381 414.10849401863 89.81538044021147 C 426.850959573546 86.22821295343913 433.222192351004 84.57196300942039 445.96465790592 81.45551257509203 C 458.705681026428 78.33941491984852 465.076192586682 76.93199291811844 477.81721570719 74.23401021628183 C 490.559681262106 71.53572207091493 496.93091403956396 70.31477791200427 509.67337959448 67.96483545708327 C 522.414402714988 65.61515901330738 528.784914275242 64.44401819752946 541.52593739575 62.484962969539595 C 554.268402950662 60.525685953343746 560.639635728118 59.726020050731215 573.38210128303 58.169004846618975 C 586.123124403538 56.61216589507641 592.493635963792 55.92201187033313 605.2346590843 54.700327580402586 C 617.977124639216 53.478504981370904 624.3483574166739 52.96769777690279 637.09082297159 52.060237624213414 C 649.831846092098 51.152880195109404 656.2023576523519 50.76029439513268 668.94338077286 50.16328362591912 C 681.6858463277761 49.5662052680302 688.0570791052339 49.42776227750982 700.79954466015 49.075014806457204 C 713.5405677806581 48.72230726606694 719.911079340912 48.43354580659462 732.65210246142 48.399646097311916 C 745.394568016336 48.36574638802921 751.765800793794 48.36574638802921 764.50826634871 48.36574638802921 C 777.249289469218 48.36574638802921 783.619801029472 48.78898020988594 796.36082414998 49.279959794090075 C 809.103289704892 49.77099496298605 815.474522482348 50.05440657597616 828.21698803726 50.820783270779486 C 840.9580111577679 51.5870732125046 847.328522718022 52.07281846449755 860.06954583853 53.11162638541117 C 872.8120113934459 54.15055191165948 879.1832441709039 54.69006337035734 891.92570972582 56.015116888684304 C 904.6681752807359 57.34017040701126 923.78187361311 59.73689397704595 923.78187361311 59.73689397704595"
                                  class="highcharts-graph" data-z-index="1" stroke="#5ef983"
                                  stroke-width="2" stroke-linejoin="round"
                                  stroke-linecap="round"></path>
                            <path fill="none"
                                  d="M -10 365 L 0 365 C 0 365 19.1136983323728 340.1946427323053 31.856163887288 326.5866833534227 C 44.5971870077956 312.9802643819865 50.9676985680494 309.45192430132624 63.708721688557 296.964054124203 C 76.45118724347219 284.4747701725775 82.8224200209298 275.91322063859866 95.564885575845 264.14379803155083 C 108.305908696351 252.37570771141964 114.676420256604 248.36453561598378 127.41744337711 238.12027180625546 C 140.159908932026 227.8748482247816 146.53114170948402 222.35051985497907 159.2736072644 212.91957955354542 C 172.014630384908 203.48970682515966 178.38514194516202 199.3251613424624 191.12616506567 190.9682392317069 C 203.868630620586 182.61037101859495 210.239863398044 178.6731672323085 222.98232895296 171.1326037438768 C 235.723352073468 163.59289383972083 242.093863633722 160.02535925542986 254.83488675423 153.2675557502377 C 267.577352309146 146.50898718181583 273.948585086604 143.36026241206778 286.69105064152 137.3416735598417 C 299.432073762028 131.32376600587858 305.80258532228197 128.5258357669175 318.54360844279 123.17631473476473 C 331.286073997702 117.8261880736049 337.657306775158 115.34981653039299 350.39977233007 110.59255432656016 C 363.140795450578 105.83583064006858 369.511307010832 103.54654957737199 382.25233013134 99.39135000895374 C 394.994795686256 95.23568002283251 401.366028463714 93.40254792698381 414.10849401863 89.81538044021147 C 426.850959573546 86.22821295343913 433.222192351004 84.57196300942039 445.96465790592 81.45551257509203 C 458.705681026428 78.33941491984852 465.076192586682 76.93199291811844 477.81721570719 74.23401021628183 C 490.559681262106 71.53572207091493 496.93091403956396 70.31477791200427 509.67337959448 67.96483545708327 C 522.414402714988 65.61515901330738 528.784914275242 64.44401819752946 541.52593739575 62.484962969539595 C 554.268402950662 60.525685953343746 560.639635728118 59.726020050731215 573.38210128303 58.169004846618975 C 586.123124403538 56.61216589507641 592.493635963792 55.92201187033313 605.2346590843 54.700327580402586 C 617.977124639216 53.478504981370904 624.3483574166739 52.96769777690279 637.09082297159 52.060237624213414 C 649.831846092098 51.152880195109404 656.2023576523519 50.76029439513268 668.94338077286 50.16328362591912 C 681.6858463277761 49.5662052680302 688.0570791052339 49.42776227750982 700.79954466015 49.075014806457204 C 713.5405677806581 48.72230726606694 719.911079340912 48.43354580659462 732.65210246142 48.399646097311916 C 745.394568016336 48.36574638802921 751.765800793794 48.36574638802921 764.50826634871 48.36574638802921 C 777.249289469218 48.36574638802921 783.619801029472 48.78898020988594 796.36082414998 49.279959794090075 C 809.103289704892 49.77099496298605 815.474522482348 50.05440657597616 828.21698803726 50.820783270779486 C 840.9580111577679 51.5870732125046 847.328522718022 52.07281846449755 860.06954583853 53.11162638541117 C 872.8120113934459 54.15055191165948 879.1832441709039 54.69006337035734 891.92570972582 56.015116888684304 C 904.6681752807359 57.34017040701126 923.78187361311 59.73689397704595 923.78187361311 59.73689397704595 L 933.78187361311 59.73689397704595"
                                  stroke-linejoin="round" stroke="rgba(192,192,192,0.0001)"
                                  stroke-width="22" visibility="visible" data-z-index="2"
                                  class="highcharts-tracker-line"></path>
                        </g>
                        <g data-z-index="0.1"
                           class="highcharts-markers highcharts-series-4 highcharts-spline-series  highcharts-tracker"
                           transform="translate(70,10) scale(1 1)"></g>
                    </g>
                    <text x="558" text-anchor="middle" class="highcharts-title" data-z-index="4"
                          style="color:#333333;font-size:18px;fill:#333333;" y="24"></text>
                    <text x="558" text-anchor="middle" class="highcharts-subtitle"
                          data-z-index="4" style="color:#666666;fill:#666666;" y="24"></text>
                    <g data-z-index="6"
                       class="highcharts-data-labels highcharts-series-0 highcharts-spline-series "
                       transform="translate(70,10) scale(1 1)" opacity="1" visibility="visible">
                        <g class="highcharts-label highcharts-data-label highcharts-data-label-color-undefined "
                           data-z-index="1" transform="translate(44,7)">
                            <text x="5" data-z-index="1"
                                  style="font-size:11px;font-weight:bold;color:#000000;fill:#000000;"
                                  y="16">
                                <tspan x="5" y="16" class="highcharts-text-outline"
                                       fill="#FFFFFF" stroke="#FFFFFF" stroke-width="2px"
                                       stroke-linejoin="round" style="">18.03
                                </tspan>
                                <tspan x="5" y="16">18.03</tspan>
                            </text>
                        </g>
                    </g>
                    <g data-z-index="6"
                       class="highcharts-data-labels highcharts-series-1 highcharts-spline-series "
                       transform="translate(70,10) scale(1 1)" opacity="1" visibility="visible">
                        <g class="highcharts-label highcharts-data-label highcharts-data-label-color-undefined "
                           data-z-index="1" transform="translate(41,63)">
                            <text x="5" data-z-index="1"
                                  style="font-size:11px;font-weight:bold;color:#000000;fill:#000000;"
                                  y="16">
                                <tspan x="5" y="16" class="highcharts-text-outline"
                                       fill="#FFFFFF" stroke="#FFFFFF" stroke-width="2px"
                                       stroke-linejoin="round">17.39
                                </tspan>
                                <tspan x="5" y="16">17.39</tspan>
                            </text>
                        </g>
                    </g>
                    <g data-z-index="6"
                       class="highcharts-data-labels highcharts-series-2 highcharts-spline-series "
                       transform="translate(70,10) scale(1 1)" opacity="1" visibility="visible">
                        <g class="highcharts-label highcharts-data-label highcharts-data-label-color-undefined "
                           data-z-index="1" transform="translate(30,219)">
                            <text x="5" data-z-index="1"
                                  style="font-size:11px;font-weight:bold;color:#000000;fill:#000000;"
                                  y="16">
                                <tspan x="5" y="16" class="highcharts-text-outline"
                                       fill="#FFFFFF" stroke="#FFFFFF" stroke-width="2px"
                                       stroke-linejoin="round">14.49
                                </tspan>
                                <tspan x="5" y="16">14.49</tspan>
                            </text>
                        </g>
                    </g>
                    <g class="highcharts-axis-labels highcharts-xaxis-labels "
                       data-z-index="7"></g>
                    <g class="highcharts-axis-labels highcharts-yaxis-labels " data-z-index="7">
                        <text x="55"
                              style="color:#666666;cursor:default;font-size:11px;fill:#666666;"
                              text-anchor="end" transform="translate(0,0)" y="380" opacity="1">
                            120
                        </text>
                        <text x="55"
                              style="color:#666666;cursor:default;font-size:11px;fill:#666666;"
                              text-anchor="end" transform="translate(0,0)" y="334" opacity="1">
                            150
                        </text>
                        <text x="55"
                              style="color:#666666;cursor:default;font-size:11px;fill:#666666;"
                              text-anchor="end" transform="translate(0,0)" y="288" opacity="1">
                            180
                        </text>
                        <text x="55"
                              style="color:#666666;cursor:default;font-size:11px;fill:#666666;"
                              text-anchor="end" transform="translate(0,0)" y="243" opacity="1">
                            210
                        </text>
                        <text x="55"
                              style="color:#666666;cursor:default;font-size:11px;fill:#666666;"
                              text-anchor="end" transform="translate(0,0)" y="197" opacity="1">
                            240
                        </text>
                        <text x="55"
                              style="color:#666666;cursor:default;font-size:11px;fill:#666666;"
                              text-anchor="end" transform="translate(0,0)" y="151" opacity="1">
                            270
                        </text>
                        <text x="55"
                              style="color:#666666;cursor:default;font-size:11px;fill:#666666;"
                              text-anchor="end" transform="translate(0,0)" y="106" opacity="1">
                            300
                        </text>
                        <text x="55"
                              style="color:#666666;cursor:default;font-size:11px;fill:#666666;"
                              text-anchor="end" transform="translate(0,0)" y="60" opacity="1">
                            330
                        </text>
                        <text x="55"
                              style="color:#666666;cursor:default;font-size:11px;fill:#666666;"
                              text-anchor="end" transform="translate(0,0)" y="15" opacity="1">
                            360
                        </text>
                    </g>
                    <g class="highcharts-axis-labels highcharts-yaxis-labels "
                       data-z-index="7"></g>
                    <g class="highcharts-axis-labels highcharts-yaxis-labels " data-z-index="7">
                        <text x="1080"
                              style="color:#666666;cursor:default;font-size:11px;fill:#666666;"
                              text-anchor="start" transform="translate(0,0)" y="380"
                              opacity="1">0
                        </text>
                        <text x="1080"
                              style="color:#666666;cursor:default;font-size:11px;fill:#666666;"
                              text-anchor="start" transform="translate(0,0)" y="136"
                              opacity="1">0.6
                        </text>
                        <text x="1080"
                              style="color:#666666;cursor:default;font-size:11px;fill:#666666;"
                              text-anchor="start" transform="translate(0,0)" y="319"
                              opacity="1">0.15
                        </text>
                        <text x="1080"
                              style="color:#666666;cursor:default;font-size:11px;fill:#666666;"
                              text-anchor="start" transform="translate(0,0)" y="258"
                              opacity="1">0.3
                        </text>
                        <text x="1080"
                              style="color:#666666;cursor:default;font-size:11px;fill:#666666;"
                              text-anchor="start" transform="translate(0,0)" y="197"
                              opacity="1">0.45
                        </text>
                        <text x="1080"
                              style="color:#666666;cursor:default;font-size:11px;fill:#666666;"
                              text-anchor="start" transform="translate(0,0)" y="75" opacity="1">
                            0.75
                        </text>
                        <text x="1080"
                              style="color:#666666;cursor:default;font-size:11px;fill:#666666;"
                              text-anchor="start" transform="translate(0,0)" y="15" opacity="1">
                            0.9
                        </text>
                    </g>
                    <g class="highcharts-axis-labels highcharts-yaxis-labels "
                       data-z-index="7"></g>
                    <g class="highcharts-axis-labels highcharts-yaxis-labels "
                       data-z-index="7"></g>
                </svg>
            </div>
            <div class="svg-wrap">
                <svg version="1.1" class="highcharts-root"
                     style="font-family:Lucida Grande, Lucida Sans Unicode, Arial, Helvetica, sans-serif;font-size:12px;"
                     xmlns="http://www.w3.org/2000/svg" width="1010" height="150"
                     viewBox="0 0 1010 150">
                    <desc>Created with Highcharts 6.2.0</desc>
                    <defs>
                        <clipPath id="highcharts-6mh5h5f-2112">
                            <rect x="0" y="0" width="930" height="85" fill="none"></rect>
                        </clipPath>
                    </defs>
                    <rect fill="#ffffff" class="highcharts-background" x="0" y="0" width="1010"
                          height="150" rx="0" ry="0"></rect>
                    <rect fill="none" class="highcharts-plot-background" x="70" y="10"
                          width="930" height="85"></rect>
                    <g class="highcharts-grid highcharts-xaxis-grid " data-z-index="1">
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 69.5 10 L 69.5 95"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 159.5 10 L 159.5 95"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 249.5 10 L 249.5 95"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 339.5 10 L 339.5 95"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 428.5 10 L 428.5 95"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 518.5 10 L 518.5 95"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 608.5 10 L 608.5 95"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 698.5 10 L 698.5 95"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 788.5 10 L 788.5 95"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 878.5 10 L 878.5 95"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 968.5 10 L 968.5 95"
                              opacity="1"></path>
                    </g>
                    <g class="highcharts-grid highcharts-yaxis-grid " data-z-index="1">
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 70 95.5 L 1000 95.5"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 70 53.5 L 1000 53.5"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 70 9.5 L 1000 9.5"
                              opacity="1"></path>
                    </g>
                    <g class="highcharts-grid highcharts-yaxis-grid " data-z-index="1"></g>
                    <rect fill="none" class="highcharts-plot-border" data-z-index="1" x="70"
                          y="10" width="930" height="85"></rect>
                    <g class="highcharts-axis highcharts-xaxis " data-z-index="2">
                        <path fill="none" class="highcharts-tick" stroke="#ccd6eb"
                              stroke-width="1" d="M 69.5 95 L 69.5 105" opacity="1"></path>
                        <path fill="none" class="highcharts-tick" stroke="#ccd6eb"
                              stroke-width="1" d="M 159.5 95 L 159.5 105" opacity="1"></path>
                        <path fill="none" class="highcharts-tick" stroke="#ccd6eb"
                              stroke-width="1" d="M 249.5 95 L 249.5 105" opacity="1"></path>
                        <path fill="none" class="highcharts-tick" stroke="#ccd6eb"
                              stroke-width="1" d="M 339.5 95 L 339.5 105" opacity="1"></path>
                        <path fill="none" class="highcharts-tick" stroke="#ccd6eb"
                              stroke-width="1" d="M 428.5 95 L 428.5 105" opacity="1"></path>
                        <path fill="none" class="highcharts-tick" stroke="#ccd6eb"
                              stroke-width="1" d="M 518.5 95 L 518.5 105" opacity="1"></path>
                        <path fill="none" class="highcharts-tick" stroke="#ccd6eb"
                              stroke-width="1" d="M 608.5 95 L 608.5 105" opacity="1"></path>
                        <path fill="none" class="highcharts-tick" stroke="#ccd6eb"
                              stroke-width="1" d="M 698.5 95 L 698.5 105" opacity="1"></path>
                        <path fill="none" class="highcharts-tick" stroke="#ccd6eb"
                              stroke-width="1" d="M 788.5 95 L 788.5 105" opacity="1"></path>
                        <path fill="none" class="highcharts-tick" stroke="#ccd6eb"
                              stroke-width="1" d="M 878.5 95 L 878.5 105" opacity="1"></path>
                        <path fill="none" class="highcharts-tick" stroke="#ccd6eb"
                              stroke-width="1" d="M 968.5 95 L 968.5 105" opacity="1"></path>
                        <text x="535" data-z-index="7" text-anchor="middle"
                              transform="translate(0,0)" class="highcharts-axis-title"
                              style="color:#666666;fill:#666666;" y="133">
                            <tspan>Flow - gal/min</tspan>
                        </text>
                        <path fill="none" class="highcharts-axis-line" stroke="#ccd6eb"
                              stroke-width="1" data-z-index="7"
                              d="M 70 95.5 L 1000 95.5"></path>
                    </g>
                    <g class="highcharts-axis highcharts-yaxis " data-z-index="2">
                        <text x="29.015625" data-z-index="7" text-anchor="middle"
                              transform="translate(0,0) rotate(270 29.015625 52.5)"
                              class="highcharts-axis-title" style="color:#666666;fill:#666666;"
                              y="52.5">
                            <tspan>NPSH - ft</tspan>
                        </text>
                        <path fill="none" class="highcharts-axis-line" stroke="#ccd6eb"
                              stroke-width="1" data-z-index="7" d="M 69.5 10 L 69.5 95"></path>
                    </g>
                    <g class="highcharts-axis highcharts-yaxis " data-z-index="2">
                        <path fill="none" class="highcharts-axis-line" stroke="#ccd6eb"
                              stroke-width="1" data-z-index="7"
                              d="M 1000.5 10 L 1000.5 95"></path>
                    </g>
                    <g class="highcharts-series-group" data-z-index="3">
                        <g data-z-index="0.1"
                           class="highcharts-series highcharts-series-0 highcharts-spline-series highcharts-color-0 "
                           transform="translate(70,10) scale(1 1)"
                           clip-path="url(#highcharts-6mh5h5f-2112)">
                            <path fill="none"
                                  d="M 0 59.36534243947881 C 0 59.36534243947881 19.051837377997202 63.651769638204016 31.753062296662 64.42006256402188 C 44.4528494493184 65.18835548983974 50.8027430256466 64.91773111218284 63.502530178303 65.18835548983974 C 76.2037550969678 65.45901050537478 82.5543675563002 65.56647306277404 95.255592474965 65.77326104700174 C 107.955379627623 65.98002562303564 114.305273203952 66.06485963629594 127.00506035661 66.22223689049373 C 139.706285275274 66.37963196165676 146.056897734606 66.45307538132553 158.75812265327 66.56019186040379 C 171.45790980592602 66.66729621400333 177.807803382254 66.70809831138023 190.50759053491 66.75778897218824 C 203.208815453574 66.80748525856636 209.559427912906 66.80865922836914 222.26065283157 66.80865922836914 C 234.960439984226 66.80865922836914 241.310333560554 66.80865922836914 254.01012071321 66.78745098925111 C 266.711345631874 66.76624275013309 273.061958091206 66.72668607309434 285.76318300987 66.64477411186327 C 298.462970162526 66.56287142298461 304.812863738854 66.49918604292782 317.51265089151 66.3779143639768 C 330.21387581017797 66.25662895563835 336.564488269512 66.19689746229933 349.26571318818 66.03838139363958 C 361.965500340836 65.87988326884094 368.315393917164 65.79643865371455 381.01518106982 65.5853788803308 C 393.716405988484 65.37429521248613 400.067018447816 65.23983163767673 412.76824336648 64.98302279056853 C 425.469468285144 64.72621394346032 431.82008074447606 64.60450096203311 444.52130566314 64.30133464478982 C 457.22109281579594 63.998202645671626 463.570986392124 63.83493291660159 476.27077354478 63.46727699966478 C 488.97199846344404 63.09957945973275 495.32261092277605 62.88541025034453 508.02383584144 62.46295100261773 C 520.723622994096 62.04053957685693 527.073516570424 61.83143085467178 539.77330372308 61.355100315945805 C 552.474528641748 60.87871585097282 558.825141101082 60.6364415383442 571.52636601975 60.081163493370305 C 584.2261531724059 59.52594830531812 590.576046748734 59.21646579488311 603.27583390139 58.5788672333806 C 615.977058820054 57.941196488184964 622.3276712793861 57.616517225653084 635.02889619805 56.89299022662494 C 647.728683350706 56.16954513013231 654.078576927034 55.7818961971747 666.77836407969 54.961436994578676 C 679.4795889983541 54.14088490630368 685.830201457686 53.71137977938518 698.53142637635 52.79046199944739 C 711.231213529006 51.869648466484875 717.581107105334 51.39694237627 730.28089425799 50.35710871232789 C 742.9821191766539 49.31715732692495 749.332731635986 48.75282111107114 762.03395655465 47.590999376084795 C 774.733743707306 46.429309158161466 781.0836372836341 45.848785249015286 793.78342443629 44.5483288300537 C 806.4846493549579 43.24772518405463 812.835261814292 42.54484496760156 825.53648673296 41.088349213683166 C 838.236273885616 39.63201833363364 844.586167461944 38.882324902384156 857.2859546146 37.2662622451339 C 869.987179533264 35.65001663049014 876.3377919925961 34.804623472059006 889.03901691126 33.00757853394814 C 901.740241829924 31.210533595837266 920.79207920792 28.281037554579576 920.79207920792 28.281037554579576"
                                  class="highcharts-graph" data-z-index="1" stroke="#7cb5ec"
                                  stroke-width="2" stroke-linejoin="round"
                                  stroke-linecap="round"></path>
                            <path fill="none"
                                  d="M -10 59.36534243947881 L 0 59.36534243947881 C 0 59.36534243947881 19.051837377997202 63.651769638204016 31.753062296662 64.42006256402188 C 44.4528494493184 65.18835548983974 50.8027430256466 64.91773111218284 63.502530178303 65.18835548983974 C 76.2037550969678 65.45901050537478 82.5543675563002 65.56647306277404 95.255592474965 65.77326104700174 C 107.955379627623 65.98002562303564 114.305273203952 66.06485963629594 127.00506035661 66.22223689049373 C 139.706285275274 66.37963196165676 146.056897734606 66.45307538132553 158.75812265327 66.56019186040379 C 171.45790980592602 66.66729621400333 177.807803382254 66.70809831138023 190.50759053491 66.75778897218824 C 203.208815453574 66.80748525856636 209.559427912906 66.80865922836914 222.26065283157 66.80865922836914 C 234.960439984226 66.80865922836914 241.310333560554 66.80865922836914 254.01012071321 66.78745098925111 C 266.711345631874 66.76624275013309 273.061958091206 66.72668607309434 285.76318300987 66.64477411186327 C 298.462970162526 66.56287142298461 304.812863738854 66.49918604292782 317.51265089151 66.3779143639768 C 330.21387581017797 66.25662895563835 336.564488269512 66.19689746229933 349.26571318818 66.03838139363958 C 361.965500340836 65.87988326884094 368.315393917164 65.79643865371455 381.01518106982 65.5853788803308 C 393.716405988484 65.37429521248613 400.067018447816 65.23983163767673 412.76824336648 64.98302279056853 C 425.469468285144 64.72621394346032 431.82008074447606 64.60450096203311 444.52130566314 64.30133464478982 C 457.22109281579594 63.998202645671626 463.570986392124 63.83493291660159 476.27077354478 63.46727699966478 C 488.97199846344404 63.09957945973275 495.32261092277605 62.88541025034453 508.02383584144 62.46295100261773 C 520.723622994096 62.04053957685693 527.073516570424 61.83143085467178 539.77330372308 61.355100315945805 C 552.474528641748 60.87871585097282 558.825141101082 60.6364415383442 571.52636601975 60.081163493370305 C 584.2261531724059 59.52594830531812 590.576046748734 59.21646579488311 603.27583390139 58.5788672333806 C 615.977058820054 57.941196488184964 622.3276712793861 57.616517225653084 635.02889619805 56.89299022662494 C 647.728683350706 56.16954513013231 654.078576927034 55.7818961971747 666.77836407969 54.961436994578676 C 679.4795889983541 54.14088490630368 685.830201457686 53.71137977938518 698.53142637635 52.79046199944739 C 711.231213529006 51.869648466484875 717.581107105334 51.39694237627 730.28089425799 50.35710871232789 C 742.9821191766539 49.31715732692495 749.332731635986 48.75282111107114 762.03395655465 47.590999376084795 C 774.733743707306 46.429309158161466 781.0836372836341 45.848785249015286 793.78342443629 44.5483288300537 C 806.4846493549579 43.24772518405463 812.835261814292 42.54484496760156 825.53648673296 41.088349213683166 C 838.236273885616 39.63201833363364 844.586167461944 38.882324902384156 857.2859546146 37.2662622451339 C 869.987179533264 35.65001663049014 876.3377919925961 34.804623472059006 889.03901691126 33.00757853394814 C 901.740241829924 31.210533595837266 920.79207920792 28.281037554579576 920.79207920792 28.281037554579576 L 930.79207920792 28.281037554579576"
                                  stroke-linejoin="round" stroke="rgba(192,192,192,0.0001)"
                                  stroke-width="22" visibility="visible" data-z-index="2"
                                  class="highcharts-tracker-line"></path>
                        </g>
                        <g data-z-index="0.1"
                           class="highcharts-markers highcharts-series-0 highcharts-spline-series highcharts-color-0 highcharts-tracker"
                           transform="translate(70,10) scale(1 1)"></g>
                    </g>
                    <text x="505" text-anchor="middle" class="highcharts-title" data-z-index="4"
                          style="color:#333333;font-size:18px;fill:#333333;" y="24"></text>
                    <text x="505" text-anchor="middle" class="highcharts-subtitle"
                          data-z-index="4" style="color:#666666;fill:#666666;" y="24"></text>
                    <g class="highcharts-axis-labels highcharts-xaxis-labels " data-z-index="7">
                        <text x="70"
                              style="color:#666666;cursor:default;font-size:11px;fill:#666666;"
                              text-anchor="middle" transform="translate(0,0)" y="114"
                              opacity="1">0
                        </text>
                        <text x="159.86037552825"
                              style="color:#666666;cursor:default;font-size:11px;fill:#666666;"
                              text-anchor="middle" transform="translate(0,0)" y="114"
                              opacity="1">250
                        </text>
                        <text x="249.7207510565"
                              style="color:#666666;cursor:default;font-size:11px;fill:#666666;"
                              text-anchor="middle" transform="translate(0,0)" y="114"
                              opacity="1">500
                        </text>
                        <text x="339.58112658475"
                              style="color:#666666;cursor:default;font-size:11px;fill:#666666;"
                              text-anchor="middle" transform="translate(0,0)" y="114"
                              opacity="1">750
                        </text>
                        <text x="429.44150211299"
                              style="color:#666666;cursor:default;font-size:11px;fill:#666666;"
                              text-anchor="middle" transform="translate(0,0)" y="114"
                              opacity="1">1000
                        </text>
                        <text x="519.30187764124"
                              style="color:#666666;cursor:default;font-size:11px;fill:#666666;"
                              text-anchor="middle" transform="translate(0,0)" y="114"
                              opacity="1">1250
                        </text>
                        <text x="609.16225316949"
                              style="color:#666666;cursor:default;font-size:11px;fill:#666666;"
                              text-anchor="middle" transform="translate(0,0)" y="114"
                              opacity="1">1500
                        </text>
                        <text x="699.02262869774"
                              style="color:#666666;cursor:default;font-size:11px;fill:#666666;"
                              text-anchor="middle" transform="translate(0,0)" y="114"
                              opacity="1">1750
                        </text>
                        <text x="788.88300422599"
                              style="color:#666666;cursor:default;font-size:11px;fill:#666666;"
                              text-anchor="middle" transform="translate(0,0)" y="114"
                              opacity="1">2000
                        </text>
                        <text x="878.74337975424"
                              style="color:#666666;cursor:default;font-size:11px;fill:#666666;"
                              text-anchor="middle" transform="translate(0,0)" y="114"
                              opacity="1">2250
                        </text>
                        <text x="968.60375528249"
                              style="color:#666666;cursor:default;font-size:11px;fill:#666666;"
                              text-anchor="middle" transform="translate(0,0)" y="114"
                              opacity="1">2500
                        </text>
                    </g>
                    <g class="highcharts-axis-labels highcharts-yaxis-labels " data-z-index="7">
                        <text x="55"
                              style="color:#666666;cursor:default;font-size:11px;fill:#666666;"
                              text-anchor="end" transform="translate(0,0)" y="100" opacity="1">0
                        </text>
                        <text x="55"
                              style="color:#666666;cursor:default;font-size:11px;fill:#666666;"
                              text-anchor="end" transform="translate(0,0)" y="57" opacity="1">25
                        </text>
                        <text x="55"
                              style="color:#666666;cursor:default;font-size:11px;fill:#666666;"
                              text-anchor="end" transform="translate(0,0)" y="15" opacity="1">50
                        </text>
                    </g>
                    <g class="highcharts-axis-labels highcharts-yaxis-labels "
                       data-z-index="7"></g>
                </svg>
            </div>
        </div>
        <div class="ten page landscape">
            <div class="text-ac">
                <p><strong>Tag: 001</strong> - SCE | Size: SCE 10x8x18</p>
            </div>
            <table class="table text-al">
                <thead class="tStrong">Pump Information</thead>
                <tbody>
                <tr>
                    <th>Tag:</th>
                    <td>001</td>
                </tr>
                <tr>
                    <th>Quantity:</th>
                    <td></td>
                </tr>
                <tr>
                    <th>Line:</th>
                    <td>SCE</td>
                </tr>
                <tr>
                    <th>Size:</th>
                    <td>MSCE 10x8x18</td>
                </tr>
                <tr>
                    <th>Service:</th>
                    <td></td>
                </tr>
                </tbody>
            </table>
            <table class="table text-al">
                <thead class="tStrong">Duty Conditions</thead>
                <tbody>
                <tr>
                    <th>
                        Flow:
                    </th>
                    <td>1500.00 gal/min</td>
                    <th>NPSHa:</th>
                    <td>40 ft</td>
                    <th>Liquid:</th>
                </tr>
                <tr>
                    <th>Head:</th>
                    <td>300 ft</td>
                    <th>Suction Pressure:</th>
                    <td>(0/0/1.01325) ft</td>
                    <th>Temperature:</th>
                    <td>(60/60/60) C</td>
                </tr>
                <tr>
                    <th>Frequency:</th>
                    <td> 60Hz/1750 RPM</td>
                    <th>vapor Pressure:</th>
                    <td>(//) ft</td>
                    <th>Sphere Diameter Size:</th>
                </tr>
                <tr>
                    <th>Speed Criteria:</th>
                    <td>Actual Speed</td>
                    <th>Density:</th>
                    <td>(0/0/1) S.G.</td>
                    <th>Solids Con by Vol:</th>
                    <td>00</td>
                </tr>
                <tr>
                    <th>Pump Operation:</th>
                    <td>-</td>
                    <th>Viscosity:</th>
                    <td>1.22 cSt</td>
                    <th> Cq/Ch/Ce/Cn:</th>
                    <td>1.00/1.00/1.00/1.00</td>
                </tr>
                </tbody>
            </table>
            <table class="table text-al">
                <thead class="tStrong">Performance Details</thead>
                <tbody>
                <tr>
                    <th>Rated Flow: <span class="span">1500 gal/min (72.15%) </span></th>
                    <th>Differential Head (Hr):<span class="span">300 ft</span></th>
                    <th>Hydraulic Power:<span class="span">113.64 hp</span></th>
                    <th>NPSHr:<span class="span">13.90 ft</span></th>
                    <th>Dmax:<span class="span">18.39</span></th>
                </tr>
                <tr>
                    <th>Normal Flow: <span class="span">-</span></th>
                    <th>Shutoff Head:<span class="span">323.32 ft</span></th>
                    <th>Rated Efficiency:<span class="span">74.57%</span></th>
                    <th>NPSHa - NPSHr:<span class="span">26.10 ft</span></th>
                    <th>Drated:<span class="span">17.39</span></th>
                </tr>
                <tr>
                    <th>BEP Flow @ Drated: <span class="span">2079.04</span></th>
                    <th>Head Rise to Shutoff: <span class="span">7.77 %</span></th>
                    <th>BHP: <span class="span">152.39 hp</span></th>
                    <th>NPSHa/NPSHr: <span class="span">2.88</span></th>
                    <th>Dmin: <span class="span">14.49</span></th>
                </tr>
                <tr>
                    <th>MCSF:<span class="span"> 121.52 gal/min</span></th>
                    <th>Hmax @ Dmax:<span class="span"> 323.58 ft</span></th>
                    <th>Pmax @ Drated:<span class="span"> 199.89 hp</span></th>
                    <th>Nss:<span class="span"> 8039.25 US Units</span></th>
                    <th>Stages Rated:<span class="span"> 1 </span></th>
                </tr>
                <tr>
                    <th>MCTF:<span class="span"> -</span></th>
                    <th>Head Ratio:<span class="span"> 9.14 %</span></th>
                    <th>Pmax @ Dmax:<span class="span"> 225.96 hp </span></th>
                    <th>Ns:<span class="span"> 1149.23 US Units</span></th>
                    <th>Stages Max:<span class="span"> 1 </span></th>
                </tr>
                </tbody>
            </table>
        </div>


        <div class="page flex j-cc a-ic">
            <h1 class="h1">
                Performance<br/> Curves
            </h1>
        </div>


        <div class="page landscape">
            <div class="svg-wrap">
                <svg version="1.1" class="highcharts-root"
                     style="font-family:&quot;Lucida Grande&quot;, &quot;Lucida Sans Unicode&quot;, Arial, Helvetica, sans-serif;font-size:12px;"
                     xmlns="http://www.w3.org/2000/svg" width="1010" height="200"
                     viewBox="0 0 1010 200">
                    <desc>Created with Highcharts 6.2.0</desc>
                    <defs>
                        <clipPath id="highcharts-6mh5h5f-1951">
                            <rect x="0" y="0" width="930" height="165" fill="none"></rect>
                        </clipPath>
                    </defs>
                    <rect fill="#ffffff" class="highcharts-background" x="0" y="0" width="1010"
                          height="200" rx="0" ry="0"></rect>
                    <rect fill="none" class="highcharts-plot-background" x="70" y="10"
                          width="930" height="165"></rect>
                    <g class="highcharts-grid highcharts-xaxis-grid " data-z-index="1">
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 69.5 10 L 69.5 175"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 159.5 10 L 159.5 175"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 249.5 10 L 249.5 175"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 339.5 10 L 339.5 175"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 428.5 10 L 428.5 175"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 518.5 10 L 518.5 175"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 608.5 10 L 608.5 175"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 698.5 10 L 698.5 175"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 788.5 10 L 788.5 175"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 878.5 10 L 878.5 175"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 968.5 10 L 968.5 175"
                              opacity="1"></path>
                    </g>
                    <g class="highcharts-grid highcharts-yaxis-grid " data-z-index="1">
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 70 175.5 L 1000 175.5"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 70 120.5 L 1000 120.5"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 70 65.5 L 1000 65.5"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 70 9.5 L 1000 9.5"
                              opacity="1"></path>
                    </g>
                    <g class="highcharts-grid highcharts-yaxis-grid " data-z-index="1"></g>
                    <rect fill="none" class="highcharts-plot-border" data-z-index="1" x="70"
                          y="10" width="930" height="165"></rect>
                    <g class="highcharts-axis highcharts-xaxis " data-z-index="2">
                        <path fill="none" class="highcharts-tick" stroke="#ccd6eb"
                              stroke-width="1" d="M 69.5 175 L 69.5 185" opacity="1"></path>
                        <path fill="none" class="highcharts-tick" stroke="#ccd6eb"
                              stroke-width="1" d="M 159.5 175 L 159.5 185" opacity="1"></path>
                        <path fill="none" class="highcharts-tick" stroke="#ccd6eb"
                              stroke-width="1" d="M 249.5 175 L 249.5 185" opacity="1"></path>
                        <path fill="none" class="highcharts-tick" stroke="#ccd6eb"
                              stroke-width="1" d="M 339.5 175 L 339.5 185" opacity="1"></path>
                        <path fill="none" class="highcharts-tick" stroke="#ccd6eb"
                              stroke-width="1" d="M 428.5 175 L 428.5 185" opacity="1"></path>
                        <path fill="none" class="highcharts-tick" stroke="#ccd6eb"
                              stroke-width="1" d="M 518.5 175 L 518.5 185" opacity="1"></path>
                        <path fill="none" class="highcharts-tick" stroke="#ccd6eb"
                              stroke-width="1" d="M 608.5 175 L 608.5 185" opacity="1"></path>
                        <path fill="none" class="highcharts-tick" stroke="#ccd6eb"
                              stroke-width="1" d="M 698.5 175 L 698.5 185" opacity="1"></path>
                        <path fill="none" class="highcharts-tick" stroke="#ccd6eb"
                              stroke-width="1" d="M 788.5 175 L 788.5 185" opacity="1"></path>
                        <path fill="none" class="highcharts-tick" stroke="#ccd6eb"
                              stroke-width="1" d="M 878.5 175 L 878.5 185" opacity="1"></path>
                        <path fill="none" class="highcharts-tick" stroke="#ccd6eb"
                              stroke-width="1" d="M 968.5 175 L 968.5 185" opacity="1"></path>
                        <path fill="none" class="highcharts-axis-line" stroke="#ccd6eb"
                              stroke-width="1" data-z-index="7"
                              d="M 70 175.5 L 1000 175.5"></path>
                    </g>
                    <g class="highcharts-axis highcharts-yaxis " data-z-index="2">
                        <text x="23.015625" data-z-index="7" text-anchor="middle"
                              transform="translate(0,0) rotate(270 23.015625 92.5)"
                              class="highcharts-axis-title" style="color:#666666;fill:#666666;"
                              y="92.5">
                            <tspan>Power - hp</tspan>
                        </text>
                        <path fill="none" class="highcharts-axis-line" stroke="#ccd6eb"
                              stroke-width="1" data-z-index="7" d="M 69.5 10 L 69.5 175"></path>
                    </g>
                    <g class="highcharts-axis highcharts-yaxis " data-z-index="2">
                        <path fill="none" class="highcharts-axis-line" stroke="#ccd6eb"
                              stroke-width="1" data-z-index="7"
                              d="M 1000.5 10 L 1000.5 175"></path>
                    </g>
                    <g class="highcharts-series-group" data-z-index="3">
                        <g data-z-index="0.1"
                           class="highcharts-series highcharts-series-0 highcharts-spline-series highcharts-color-0 "
                           transform="translate(70,10) scale(1 1)"
                           clip-path="url(#highcharts-6mh5h5f-1951)">
                            <path fill="none"
                                  d="M 0 144.76749185358975 C 0 144.76749185358975 19.051837377997202 128.47712610308812 31.753062296662 123.08666396164986 C 44.4528494493184 117.6962018202116 50.8027430256466 118.2428301544742 63.502530178303 117.6962018202116 C 76.2037550969678 117.14957348594899 82.5543675563002 117.6962018202116 95.255592474965 117.14957348594899 C 107.955379627623 116.60294515168638 114.305273203952 115.29835820652448 127.00506035661 114.3145286438774 C 139.706285275274 113.3305877000958 146.056897734606 113.14209185155629 158.75812265327 112.23014721987732 C 171.45790980592602 111.31830581942219 177.807803382254 110.73824574650388 190.50759053491 109.75506356354214 C 203.208815453574 108.77177007273679 209.559427912906 108.29848889749503 222.26065283157 107.31395803545954 C 234.960439984226 106.32953862133684 241.310333560554 105.84202729771715 254.01012071321 104.83268787314663 C 266.711345631874 103.82323417942358 273.061958091206 103.29641313701507 285.76318300987 102.26697523972558 C 298.462970162526 101.23765387378056 304.812863738854 100.71979464157498 317.51265089151 99.68578971506035 C 330.21387581017797 98.65166772696652 336.564488269512 98.14236693846131 349.26571318818 97.09665795320446 C 361.965500340836 96.05106734116333 368.315393917164 95.52366585978274 381.01518106982 94.45754072181539 C 393.716405988484 93.3912948858816 400.067018447816 92.84215976493927 412.76824336648 91.7657305184516 C 425.469468285144 90.68930127196396 431.82008074447606 90.15588999524702 444.52130566314 89.07539448937708 C 457.22109281579594 87.99502129452202 463.570986392124 87.43993732151209 476.27077354478 86.36355876663913 C 488.97199846344404 85.28705835299175 495.32261092277605 84.73892334721175 508.02383584144 83.6931970680762 C 520.723622994096 82.64758916411371 527.073516570424 82.15994176531119 539.77330372308 81.13522330889404 C 552.474528641748 80.11038884223586 558.825141101082 79.59872555599586 571.52636601975 78.5693147603879 C 584.2261531724059 77.54002049305684 590.576046748734 77.01097860881644 603.27583390139 75.98846065154652 C 615.977058820054 74.9658269331584 622.3276712793861 74.45065909912064 635.02889619805 73.45643557124278 C 647.728683350706 72.46232458847783 654.078576927034 71.98356890175667 666.77836407969 71.01762437493947 C 679.4795889983541 70.05157049178509 685.830201457686 69.54807483481947 698.53142637635 68.62643954631382 C 711.231213529006 67.7049085860047 717.581107105334 67.27640078977346 730.28089425799 66.40970875290253 C 742.9821191766539 65.54291859624935 749.332731635986 65.13470060864074 762.03395655465 64.29273406250354 C 774.733743707306 63.4508628261406 781.0836372836341 63.01014882245455 793.78342443629 62.200114296652146 C 806.4846493549579 61.38998806536714 812.835261814292 61.00716216098411 825.53648673296 60.242332169785016 C 838.236273885616 59.47758875657926 844.586167461944 59.08954155120895 857.2859546146 58.37618078564003 C 869.987179533264 57.66273925920103 876.3377919925961 57.33887015089095 889.03901691126 56.675326439765215 C 901.740241829924 56.01178272863948 920.79207920792 55.05846223001137 920.79207920792 55.05846223001137"
                                  class="highcharts-graph" data-z-index="1" stroke="#7cb5ec"
                                  stroke-width="2" stroke-linejoin="round"
                                  stroke-linecap="round"></path>
                            <path fill="none"
                                  d="M -10 144.76749185358975 L 0 144.76749185358975 C 0 144.76749185358975 19.051837377997202 128.47712610308812 31.753062296662 123.08666396164986 C 44.4528494493184 117.6962018202116 50.8027430256466 118.2428301544742 63.502530178303 117.6962018202116 C 76.2037550969678 117.14957348594899 82.5543675563002 117.6962018202116 95.255592474965 117.14957348594899 C 107.955379627623 116.60294515168638 114.305273203952 115.29835820652448 127.00506035661 114.3145286438774 C 139.706285275274 113.3305877000958 146.056897734606 113.14209185155629 158.75812265327 112.23014721987732 C 171.45790980592602 111.31830581942219 177.807803382254 110.73824574650388 190.50759053491 109.75506356354214 C 203.208815453574 108.77177007273679 209.559427912906 108.29848889749503 222.26065283157 107.31395803545954 C 234.960439984226 106.32953862133684 241.310333560554 105.84202729771715 254.01012071321 104.83268787314663 C 266.711345631874 103.82323417942358 273.061958091206 103.29641313701507 285.76318300987 102.26697523972558 C 298.462970162526 101.23765387378056 304.812863738854 100.71979464157498 317.51265089151 99.68578971506035 C 330.21387581017797 98.65166772696652 336.564488269512 98.14236693846131 349.26571318818 97.09665795320446 C 361.965500340836 96.05106734116333 368.315393917164 95.52366585978274 381.01518106982 94.45754072181539 C 393.716405988484 93.3912948858816 400.067018447816 92.84215976493927 412.76824336648 91.7657305184516 C 425.469468285144 90.68930127196396 431.82008074447606 90.15588999524702 444.52130566314 89.07539448937708 C 457.22109281579594 87.99502129452202 463.570986392124 87.43993732151209 476.27077354478 86.36355876663913 C 488.97199846344404 85.28705835299175 495.32261092277605 84.73892334721175 508.02383584144 83.6931970680762 C 520.723622994096 82.64758916411371 527.073516570424 82.15994176531119 539.77330372308 81.13522330889404 C 552.474528641748 80.11038884223586 558.825141101082 79.59872555599586 571.52636601975 78.5693147603879 C 584.2261531724059 77.54002049305684 590.576046748734 77.01097860881644 603.27583390139 75.98846065154652 C 615.977058820054 74.9658269331584 622.3276712793861 74.45065909912064 635.02889619805 73.45643557124278 C 647.728683350706 72.46232458847783 654.078576927034 71.98356890175667 666.77836407969 71.01762437493947 C 679.4795889983541 70.05157049178509 685.830201457686 69.54807483481947 698.53142637635 68.62643954631382 C 711.231213529006 67.7049085860047 717.581107105334 67.27640078977346 730.28089425799 66.40970875290253 C 742.9821191766539 65.54291859624935 749.332731635986 65.13470060864074 762.03395655465 64.29273406250354 C 774.733743707306 63.4508628261406 781.0836372836341 63.01014882245455 793.78342443629 62.200114296652146 C 806.4846493549579 61.38998806536714 812.835261814292 61.00716216098411 825.53648673296 60.242332169785016 C 838.236273885616 59.47758875657926 844.586167461944 59.08954155120895 857.2859546146 58.37618078564003 C 869.987179533264 57.66273925920103 876.3377919925961 57.33887015089095 889.03901691126 56.675326439765215 C 901.740241829924 56.01178272863948 920.79207920792 55.05846223001137 920.79207920792 55.05846223001137 L 930.79207920792 55.05846223001137"
                                  stroke-linejoin="round" stroke="rgba(192,192,192,0.0001)"
                                  stroke-width="22" visibility="visible" data-z-index="2"
                                  class="highcharts-tracker-line"></path>
                        </g>
                        <g data-z-index="0.1"
                           class="highcharts-markers highcharts-series-0 highcharts-spline-series highcharts-color-0 highcharts-tracker"
                           transform="translate(70,10) scale(1 1)"></g>
                    </g>
                    <text x="505" text-anchor="middle" class="highcharts-title" data-z-index="4"
                          style="color:#333333;font-size:18px;fill:#333333;" y="24"></text>
                    <text x="505" text-anchor="middle" class="highcharts-subtitle"
                          data-z-index="4" style="color:#666666;fill:#666666;" y="24"></text>
                    <g class="highcharts-axis-labels highcharts-xaxis-labels "
                       data-z-index="7"></g>
                    <g class="highcharts-axis-labels highcharts-yaxis-labels " data-z-index="7">
                        <text x="55"
                              style="color:#666666;cursor:default;font-size:11px;fill:#666666;"
                              text-anchor="end" transform="translate(0,0)" y="180" opacity="1">0
                        </text>
                        <text x="55"
                              style="color:#666666;cursor:default;font-size:11px;fill:#666666;"
                              text-anchor="end" transform="translate(0,0)" y="125" opacity="1">
                            100
                        </text>
                        <text x="55"
                              style="color:#666666;cursor:default;font-size:11px;fill:#666666;"
                              text-anchor="end" transform="translate(0,0)" y="70" opacity="1">
                            200
                        </text>
                        <text x="55"
                              style="color:#666666;cursor:default;font-size:11px;fill:#666666;"
                              text-anchor="end" transform="translate(0,0)" y="15" opacity="1">
                            300
                        </text>
                    </g>
                    <g class="highcharts-axis-labels highcharts-yaxis-labels "
                       data-z-index="7"></g>
                </svg>
            </div>
            <div class="svg-wrap">
                <svg version="1.1" class="highcharts-root"
                     style="font-family:&quot;Lucida Grande&quot;, &quot;Lucida Sans Unicode&quot;, Arial, Helvetica, sans-serif;font-size:12px;"
                     xmlns="http://www.w3.org/2000/svg" width="1116" height="400"
                     viewBox="0 0 1116 400">
                    <desc>Created with Highcharts 6.2.0</desc>
                    <defs>
                        <clipPath id="highcharts-6mh5h5f-1985">
                            <rect x="0" y="0" width="971" height="365" fill="none"></rect>
                        </clipPath>
                    </defs>
                    <rect fill="#ffffff" class="highcharts-background" x="0" y="0" width="1116"
                          height="400" rx="0" ry="0"></rect>
                    <rect fill="none" class="highcharts-plot-background" x="70" y="10"
                          width="971" height="365"></rect>
                    <g class="highcharts-grid highcharts-xaxis-grid " data-z-index="1">
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 69.5 10 L 69.5 375"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 159.5 10 L 159.5 375"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 249.5 10 L 249.5 375"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 339.5 10 L 339.5 375"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 430.5 10 L 430.5 375"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 520.5 10 L 520.5 375"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 610.5 10 L 610.5 375"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 700.5 10 L 700.5 375"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 790.5 10 L 790.5 375"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 880.5 10 L 880.5 375"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 971.5 10 L 971.5 375"
                              opacity="1"></path>
                    </g>
                    <g class="highcharts-grid highcharts-yaxis-grid " data-z-index="1">
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 70 375.5 L 1041 375.5"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 70 329.5 L 1041 329.5"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 70 284.5 L 1041 284.5"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 70 238.5 L 1041 238.5"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 70 193.5 L 1041 193.5"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 70 147.5 L 1041 147.5"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 70 101.5 L 1041 101.5"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 70 56.5 L 1041 56.5"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 70 9.5 L 1041 9.5"
                              opacity="1"></path>
                    </g>
                    <g class="highcharts-grid highcharts-yaxis-grid " data-z-index="1"></g>
                    <g class="highcharts-grid highcharts-yaxis-grid " data-z-index="1">
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 70 375.5 L 1041 375.5"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 70 132.5 L 1041 132.5"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 70 314.5 L 1041 314.5"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 70 253.5 L 1041 253.5"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 70 193.5 L 1041 193.5"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 70 71.5 L 1041 71.5"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 70 9.5 L 1041 9.5"
                              opacity="1"></path>
                    </g>
                    <g class="highcharts-grid highcharts-yaxis-grid " data-z-index="1"></g>
                    <g class="highcharts-grid highcharts-yaxis-grid " data-z-index="1"></g>
                    <rect fill="none" class="highcharts-plot-border" data-z-index="1" x="70"
                          y="10" width="971" height="365"></rect>
                    <g class="highcharts-axis highcharts-xaxis " data-z-index="2">
                        <path fill="none" class="highcharts-tick" stroke="#ccd6eb"
                              stroke-width="1" d="M 69.5 375 L 69.5 385" opacity="1"></path>
                        <path fill="none" class="highcharts-tick" stroke="#ccd6eb"
                              stroke-width="1" d="M 159.5 375 L 159.5 385" opacity="1"></path>
                        <path fill="none" class="highcharts-tick" stroke="#ccd6eb"
                              stroke-width="1" d="M 249.5 375 L 249.5 385" opacity="1"></path>
                        <path fill="none" class="highcharts-tick" stroke="#ccd6eb"
                              stroke-width="1" d="M 339.5 375 L 339.5 385" opacity="1"></path>
                        <path fill="none" class="highcharts-tick" stroke="#ccd6eb"
                              stroke-width="1" d="M 430.5 375 L 430.5 385" opacity="1"></path>
                        <path fill="none" class="highcharts-tick" stroke="#ccd6eb"
                              stroke-width="1" d="M 520.5 375 L 520.5 385" opacity="1"></path>
                        <path fill="none" class="highcharts-tick" stroke="#ccd6eb"
                              stroke-width="1" d="M 610.5 375 L 610.5 385" opacity="1"></path>
                        <path fill="none" class="highcharts-tick" stroke="#ccd6eb"
                              stroke-width="1" d="M 700.5 375 L 700.5 385" opacity="1"></path>
                        <path fill="none" class="highcharts-tick" stroke="#ccd6eb"
                              stroke-width="1" d="M 790.5 375 L 790.5 385" opacity="1"></path>
                        <path fill="none" class="highcharts-tick" stroke="#ccd6eb"
                              stroke-width="1" d="M 880.5 375 L 880.5 385" opacity="1"></path>
                        <path fill="none" class="highcharts-tick" stroke="#ccd6eb"
                              stroke-width="1" d="M 971.5 375 L 971.5 385" opacity="1"></path>
                        <path fill="none" class="highcharts-axis-line" stroke="#ccd6eb"
                              stroke-width="1" data-z-index="7"
                              d="M 70 375.5 L 1041 375.5"></path>
                    </g>
                    <g class="highcharts-axis highcharts-yaxis " data-z-index="2">
                        <text x="23.015625" data-z-index="7" text-anchor="middle"
                              transform="translate(0,0) rotate(270 23.015625 192.5)"
                              class="highcharts-axis-title" style="color:#666666;fill:#666666;"
                              y="192.5">
                            <tspan>Head - ft</tspan>
                        </text>
                        <path fill="none" class="highcharts-axis-line" data-z-index="7"
                              d="M 70 10 L 70 375"></path>
                    </g>
                    <g class="highcharts-axis highcharts-yaxis " data-z-index="2">
                        <text x="1051" data-z-index="7" text-anchor="middle"
                              transform="translate(0,0) rotate(90 1051 192.5)"
                              class="highcharts-axis-title" style="color:#666666;fill:#666666;"
                              y="192.5">
                            <tspan>Efficiency %</tspan>
                        </text>
                        <path fill="none" class="highcharts-axis-line" stroke="#ccd6eb"
                              stroke-width="1" data-z-index="7"
                              d="M 1041.5 10 L 1041.5 375"></path>
                    </g>
                    <g class="highcharts-axis highcharts-yaxis " data-z-index="2">
                        <path fill="none" class="highcharts-axis-line" data-z-index="7"
                              d="M 1065 10 L 1065 375"></path>
                    </g>
                    <g class="highcharts-axis highcharts-yaxis " data-z-index="2">
                        <path fill="none" class="highcharts-axis-line" data-z-index="7"
                              d="M 1106 10 L 1106 375"></path>
                    </g>
                    <g class="highcharts-axis highcharts-yaxis " data-z-index="2">
                        <path fill="none" class="highcharts-axis-line" data-z-index="7"
                              d="M 1106 10 L 1106 375"></path>
                    </g>
                    <g class="highcharts-series-group" data-z-index="3">
                        <g data-z-index="0.1"
                           class="highcharts-series highcharts-series-0 highcharts-spline-series "
                           transform="translate(70,10) scale(1 1)"
                           clip-path="url(#highcharts-6mh5h5f-1985)">
                            <path fill="none"
                                  d="M 0 16.904724594987727 C 0 16.904724594987727 19.8904492607544 16.421227949654224 33.150748767924 16.421227949654224 C 46.4110482750932 16.421227949654224 53.04119802867781 16.65789904828049 66.301497535847 16.75006008174182 C 79.5617970430166 16.842221115203156 86.1919467966014 16.80718435796472 99.452246303771 16.882033116960883 C 112.7139882453466 16.956890017886657 119.34485921613441 16.899632201605606 132.60660115771 17.124324231546666 C 145.866900664882 17.34899182250259 152.497050418468 17.67052405077241 165.75734992564 18.005432169203345 C 179.017649432808 18.340340287634177 185.647799186392 18.329298270102402 198.90809869356 18.79886482370108 C 212.168398200728 19.268431377299763 218.79854795431203 19.714908760628514 232.05884746148 20.35326493719674 C 245.319146968652 20.99162111376516 251.94929672223802 21.3233552731331 265.20959622941 21.990645706542693 C 278.469895736578 22.657936139952085 285.100045490162 22.88150629902967 298.36034499733 23.68971710424421 C 311.62064450450197 24.497927909458994 318.250794258088 24.991784560243513 331.51109376526 26.031699732616005 C 344.77283570683596 27.071728025315906 351.403706677624 27.76035091381759 364.6654486192 28.88957576692519 C 377.9257481263679 30.01867779809961 384.555897879952 30.417982333114104 397.81619738712 31.677516943321052 C 411.076496894292 32.937051553528384 417.706646647878 33.69864178872074 430.96694615505 35.18724881796089 C 444.22724566221797 36.675855847200594 450.857395415802 37.5008101441869 464.11769492297 39.120552089520686 C 477.377994430138 40.740294034854486 484.00814418372204 41.52687338200739 497.26844369089 43.285958544629864 C 510.528743198062 45.045043707252866 517.1588929516481 45.916969443756564 530.41919245882 47.91597790263438 C 543.6794919659881 49.91498636151162 550.309641719572 51.00221134013895 563.56994122674 53.28100083901751 C 576.831683168316 55.56003822101365 583.462554139104 56.88328161838885 596.72429608068 59.31054510482113 C 609.984595587852 61.73754458608909 616.614745341438 62.865343660295295 629.87504484861 65.41665825826811 C 643.135344355778 67.9679728562402 649.7654941093621 69.27119638117874 663.02579361653 72.0671180946834 C 676.286093123698 74.86303980818806 682.9162428772821 76.36388452547419 696.17654238445 79.39626682579143 C 709.4368418916221 82.4286491261096 716.066991645208 83.98418203938404 729.32729115238 87.22902959627191 C 742.587590659548 90.47387715315881 749.217740413132 92.15924452188898 762.4780399203 95.62050461022835 C 775.7383394274681 99.08176469856772 782.3684891810519 100.85372374376443 795.62878868822 104.53533003796878 C 808.8905306298 108.21733681148409 815.52140160059 110.10722695644235 828.78314354217 114.02953727952749 C 842.0434430493381 117.95142098630465 848.673592802922 119.98470997287545 861.93389231009 124.14581511262458 C 875.1941918172579 128.3069202523737 881.8243415708421 130.43261705026373 895.08464107801 134.83506297827302 C 908.3449405851819 139.23750890628364 914.9750903387679 141.51683178164177 928.23538984594 146.15804475267436 C 941.495689353108 150.79925772370558 961.38613861386 158.04112783343254 961.38613861386 158.04112783343254"
                                  class="highcharts-graph" data-z-index="1" stroke="black"
                                  stroke-width="2" stroke-linejoin="round"
                                  stroke-linecap="round"></path>
                            <path fill="none"
                                  d="M -10 16.904724594987727 L 0 16.904724594987727 C 0 16.904724594987727 19.8904492607544 16.421227949654224 33.150748767924 16.421227949654224 C 46.4110482750932 16.421227949654224 53.04119802867781 16.65789904828049 66.301497535847 16.75006008174182 C 79.5617970430166 16.842221115203156 86.1919467966014 16.80718435796472 99.452246303771 16.882033116960883 C 112.7139882453466 16.956890017886657 119.34485921613441 16.899632201605606 132.60660115771 17.124324231546666 C 145.866900664882 17.34899182250259 152.497050418468 17.67052405077241 165.75734992564 18.005432169203345 C 179.017649432808 18.340340287634177 185.647799186392 18.329298270102402 198.90809869356 18.79886482370108 C 212.168398200728 19.268431377299763 218.79854795431203 19.714908760628514 232.05884746148 20.35326493719674 C 245.319146968652 20.99162111376516 251.94929672223802 21.3233552731331 265.20959622941 21.990645706542693 C 278.469895736578 22.657936139952085 285.100045490162 22.88150629902967 298.36034499733 23.68971710424421 C 311.62064450450197 24.497927909458994 318.250794258088 24.991784560243513 331.51109376526 26.031699732616005 C 344.77283570683596 27.071728025315906 351.403706677624 27.76035091381759 364.6654486192 28.88957576692519 C 377.9257481263679 30.01867779809961 384.555897879952 30.417982333114104 397.81619738712 31.677516943321052 C 411.076496894292 32.937051553528384 417.706646647878 33.69864178872074 430.96694615505 35.18724881796089 C 444.22724566221797 36.675855847200594 450.857395415802 37.5008101441869 464.11769492297 39.120552089520686 C 477.377994430138 40.740294034854486 484.00814418372204 41.52687338200739 497.26844369089 43.285958544629864 C 510.528743198062 45.045043707252866 517.1588929516481 45.916969443756564 530.41919245882 47.91597790263438 C 543.6794919659881 49.91498636151162 550.309641719572 51.00221134013895 563.56994122674 53.28100083901751 C 576.831683168316 55.56003822101365 583.462554139104 56.88328161838885 596.72429608068 59.31054510482113 C 609.984595587852 61.73754458608909 616.614745341438 62.865343660295295 629.87504484861 65.41665825826811 C 643.135344355778 67.9679728562402 649.7654941093621 69.27119638117874 663.02579361653 72.0671180946834 C 676.286093123698 74.86303980818806 682.9162428772821 76.36388452547419 696.17654238445 79.39626682579143 C 709.4368418916221 82.4286491261096 716.066991645208 83.98418203938404 729.32729115238 87.22902959627191 C 742.587590659548 90.47387715315881 749.217740413132 92.15924452188898 762.4780399203 95.62050461022835 C 775.7383394274681 99.08176469856772 782.3684891810519 100.85372374376443 795.62878868822 104.53533003796878 C 808.8905306298 108.21733681148409 815.52140160059 110.10722695644235 828.78314354217 114.02953727952749 C 842.0434430493381 117.95142098630465 848.673592802922 119.98470997287545 861.93389231009 124.14581511262458 C 875.1941918172579 128.3069202523737 881.8243415708421 130.43261705026373 895.08464107801 134.83506297827302 C 908.3449405851819 139.23750890628364 914.9750903387679 141.51683178164177 928.23538984594 146.15804475267436 C 941.495689353108 150.79925772370558 961.38613861386 158.04112783343254 961.38613861386 158.04112783343254 L 971.38613861386 158.04112783343254"
                                  stroke-linejoin="round" stroke="rgba(192,192,192,0.0001)"
                                  stroke-width="22" visibility="visible" data-z-index="2"
                                  class="highcharts-tracker-line"></path>
                        </g>
                        <g data-z-index="0.1"
                           class="highcharts-markers highcharts-series-0 highcharts-spline-series  highcharts-tracker"
                           transform="translate(70,10) scale(1 1)"></g>
                        <g data-z-index="0.1"
                           class="highcharts-series highcharts-series-1 highcharts-spline-series "
                           transform="translate(70,10) scale(1 1)"
                           clip-path="url(#highcharts-6mh5h5f-1985)">
                            <path fill="none"
                                  d="M 0 55.78433017358901 C 0 55.78433017358901 19.1136983323728 55.3888436102788 31.856163887288 55.3888436102788 C 44.5971870077956 55.3888436102788 50.9676985680494 55.56582921372388 63.708721688557 55.64893096744299 C 76.45118724347219 55.73204212926283 82.8224200209298 55.71636603578949 95.564885575845 55.80437589912617 C 108.305908696351 55.89237579983398 114.676420256604 55.86776773958907 127.41744337711 56.088955377554214 C 140.159908932026 56.310168056574305 146.53114170948402 56.58366893982341 159.2736072644 56.91037669158925 C 172.014630384908 57.237047460363016 178.38514194516202 57.26898446445267 191.12616506567 57.722401678903225 C 203.868630620586 58.17587022554156 210.239863398044 58.567833999698564 222.98232895296 59.17759109431148 C 235.723352073468 59.787279165028664 242.093863633722 60.11208575970241 254.83488675423 60.77101459222848 C 267.577352309146 61.43001802328652 273.948585086604 61.679560693221916 286.69105064152 62.47242175327176 C 299.432073762028 63.265193062239376 305.80258532228197 63.73322205496035 318.54360844279 64.73509551477213 C 331.286073997702 65.73708239850073 337.657306775158 66.37788695976329 350.39977233007 67.48207261212269 C 363.140795450578 68.5861332717665 369.511307010832 69.01858415844288 382.25233013134 70.25571129478016 C 394.994795686256 71.49297848853134 401.366028463714 72.2207231735291 414.10849401863 73.66805843734386 C 426.850959573546 75.11539370115861 433.222192351004 75.90862668587096 445.96465790592 77.49238761385396 C 458.705681026428 79.07596926167751 465.076192586682 79.8578411794345 477.81721570719 81.58641487686026 C 490.559681262106 83.31518426925922 496.93091403956396 84.18273637533397 509.67337959448 86.13574533841575 C 522.414402714988 88.08853322282827 528.784914275242 89.14272425355006 541.52593739575 91.350906995596 C 554.268402950662 93.55933973002696 560.639635728118 94.81283364650271 573.38210128303 97.17728402960802 C 586.123124403538 99.54146675928592 592.493635963792 100.67050546697115 605.2346590843 103.17248977755406 C 617.977124639216 105.6747573423328 624.3483574166739 106.95567255859036 637.09082297159 109.68791371801211 C 649.831846092098 112.41984559045619 656.2023576523519 113.87223204151638 668.94338077286 116.83292235721868 C 681.6858463277761 119.79394785805817 688.0570791052339 121.32016257405654 700.79954466015 124.49220325936662 C 713.5405677806581 127.6638848728308 719.911079340912 129.31154177851383 732.65210246142 132.69222810415428 C 745.394568016336 136.07329716344438 751.765800793794 137.79707839803558 764.50826634871 141.39659172169297 C 777.249289469218 144.99569758402762 783.619801029472 146.851941370361 796.36082414998 150.68877606913432 C 809.103289704892 154.52604514294325 815.474522482348 156.51137486552912 828.21698803726 160.58185115314856 C 840.9580111577679 164.65186666690812 847.328522718022 166.73110430513333 860.06954583853 171.04000557258183 C 872.8120113934459 175.34939465858224 879.1832441709039 177.58083033564742 891.92570972582 182.1275770367709 C 904.6681752807359 186.67432373789433 923.78187361311 193.77373907819916 923.78187361311 193.77373907819916"
                                  class="highcharts-graph" data-z-index="1" stroke="#24CBE5"
                                  stroke-width="2" stroke-linejoin="round"
                                  stroke-linecap="round"></path>
                            <path fill="none"
                                  d="M -10 55.78433017358901 L 0 55.78433017358901 C 0 55.78433017358901 19.1136983323728 55.3888436102788 31.856163887288 55.3888436102788 C 44.5971870077956 55.3888436102788 50.9676985680494 55.56582921372388 63.708721688557 55.64893096744299 C 76.45118724347219 55.73204212926283 82.8224200209298 55.71636603578949 95.564885575845 55.80437589912617 C 108.305908696351 55.89237579983398 114.676420256604 55.86776773958907 127.41744337711 56.088955377554214 C 140.159908932026 56.310168056574305 146.53114170948402 56.58366893982341 159.2736072644 56.91037669158925 C 172.014630384908 57.237047460363016 178.38514194516202 57.26898446445267 191.12616506567 57.722401678903225 C 203.868630620586 58.17587022554156 210.239863398044 58.567833999698564 222.98232895296 59.17759109431148 C 235.723352073468 59.787279165028664 242.093863633722 60.11208575970241 254.83488675423 60.77101459222848 C 267.577352309146 61.43001802328652 273.948585086604 61.679560693221916 286.69105064152 62.47242175327176 C 299.432073762028 63.265193062239376 305.80258532228197 63.73322205496035 318.54360844279 64.73509551477213 C 331.286073997702 65.73708239850073 337.657306775158 66.37788695976329 350.39977233007 67.48207261212269 C 363.140795450578 68.5861332717665 369.511307010832 69.01858415844288 382.25233013134 70.25571129478016 C 394.994795686256 71.49297848853134 401.366028463714 72.2207231735291 414.10849401863 73.66805843734386 C 426.850959573546 75.11539370115861 433.222192351004 75.90862668587096 445.96465790592 77.49238761385396 C 458.705681026428 79.07596926167751 465.076192586682 79.8578411794345 477.81721570719 81.58641487686026 C 490.559681262106 83.31518426925922 496.93091403956396 84.18273637533397 509.67337959448 86.13574533841575 C 522.414402714988 88.08853322282827 528.784914275242 89.14272425355006 541.52593739575 91.350906995596 C 554.268402950662 93.55933973002696 560.639635728118 94.81283364650271 573.38210128303 97.17728402960802 C 586.123124403538 99.54146675928592 592.493635963792 100.67050546697115 605.2346590843 103.17248977755406 C 617.977124639216 105.6747573423328 624.3483574166739 106.95567255859036 637.09082297159 109.68791371801211 C 649.831846092098 112.41984559045619 656.2023576523519 113.87223204151638 668.94338077286 116.83292235721868 C 681.6858463277761 119.79394785805817 688.0570791052339 121.32016257405654 700.79954466015 124.49220325936662 C 713.5405677806581 127.6638848728308 719.911079340912 129.31154177851383 732.65210246142 132.69222810415428 C 745.394568016336 136.07329716344438 751.765800793794 137.79707839803558 764.50826634871 141.39659172169297 C 777.249289469218 144.99569758402762 783.619801029472 146.851941370361 796.36082414998 150.68877606913432 C 809.103289704892 154.52604514294325 815.474522482348 156.51137486552912 828.21698803726 160.58185115314856 C 840.9580111577679 164.65186666690812 847.328522718022 166.73110430513333 860.06954583853 171.04000557258183 C 872.8120113934459 175.34939465858224 879.1832441709039 177.58083033564742 891.92570972582 182.1275770367709 C 904.6681752807359 186.67432373789433 923.78187361311 193.77373907819916 923.78187361311 193.77373907819916 L 933.78187361311 193.77373907819916"
                                  stroke-linejoin="round" stroke="rgba(192,192,192,0.0001)"
                                  stroke-width="22" visibility="visible" data-z-index="2"
                                  class="highcharts-tracker-line"></path>
                        </g>
                        <g data-z-index="0.1"
                           class="highcharts-markers highcharts-series-1 highcharts-spline-series  highcharts-tracker"
                           transform="translate(70,10) scale(1 1)"></g>
                        <g data-z-index="0.1"
                           class="highcharts-series highcharts-series-2 highcharts-spline-series "
                           transform="translate(70,10) scale(1 1)"
                           clip-path="url(#highcharts-6mh5h5f-1985)">
                            <path fill="none"
                                  d="M 0 212.2646669470343 C 0 212.2646669470343 15.6345465417396 212.17543358772798 26.057577569566 212.17543358772798 C 36.48060859739199 212.17543358772798 41.692124111305 212.17543358772798 52.115155139131 212.19957737111088 C 62.538186166957395 212.22372115449377 67.7497016808706 212.29534509906364 78.172732708697 212.4192609371524 C 88.5957637365222 212.5431767752411 93.8072792504348 212.62383080963198 104.23031027826 212.81915656155462 C 114.65334130608801 213.0144823134773 119.864856820002 213.1172476467008 130.28788784783 213.39588969676566 C 140.710918875654 213.6745317468304 145.922434389566 213.84059356871816 156.34546541739 214.21236681187872 C 166.76849644521798 214.58414005503946 171.98001195913199 214.7770149570616 182.40304298696 215.25475591256892 C 192.827516449192 215.732562982241 198.03975318030803 216.01321512873696 208.46422664254 216.6012368748273 C 218.88725767036803 217.18917725634802 224.09877318428198 217.50445548826943 234.52180421211 218.1946612315966 C 244.94483523993398 218.88486697492348 250.15635075384597 219.23903262626877 260.57938178167 220.05226559146237 C 271.002412809498 220.8654985566563 276.213928323412 221.31165165498945 286.63695935124 222.26082605756545 C 297.05999037906804 223.21000046014146 302.27150589298196 223.7169261814997 312.69453692081 224.79813760434234 C 323.117567948634 225.8793490271846 328.329083462546 226.45029362447914 338.75211449037 227.66688317177778 C 349.175145518198 228.88347271907688 354.386661032112 229.5221016163931 364.80969205994 230.8810853408368 C 375.232723087764 232.24006906527998 380.444238601676 232.95134349606164 390.8672696295 234.46180179399502 C 401.290300657328 235.97226009192897 406.501816171242 236.7648974015686 416.92484719907 238.43337683050515 C 427.34787822689395 240.10185625944106 432.559393740806 240.97625163830514 442.98242476863 242.80419893867617 C 453.40545579645806 244.63214623904793 458.616971310372 245.57812181317036 469.0400023382 247.57311333236208 C 479.46303336602807 249.5681048515538 484.674548879942 250.61665934326103 495.09757990777 252.77915653463486 C 505.52061093559405 254.94165372600787 510.732126449506 256.0582334918197 521.15515747733 258.38559928922916 C 531.578188505158 260.71296508663954 536.789704019072 261.9043947729788 547.2127350469 264.41598552168443 C 557.6372085091319 266.9279238472988 562.8494452402481 268.24632650361934 573.27391870248 270.9444219750293 C 583.696949730308 273.64214411096594 588.9084652442219 275.04234702616526 599.33149627205 277.90552954005096 C 609.7545272998739 280.76871205393553 614.9660428137861 282.208708019911 625.38907384161 285.2603345444551 C 635.812104869438 288.31196106900035 641.023620383352 289.9087630914804 651.44665141118 293.1636621627743 C 661.869682439004 296.4185612340669 667.081197952916 298.09247914417506 677.50422898074 301.5348299009213 C 687.927260008568 304.9771806576689 693.1387755224821 306.73284339308333 703.56180655031 310.37541594650895 C 713.9848375781341 314.0179884999332 719.196353092046 315.9053091735226 729.61938411987 319.74769266804606 C 740.042415147698 323.590076162571 755.67696168944 329.58733341912983 755.67696168944 329.58733341912983"
                                  class="highcharts-graph" data-z-index="1" stroke="black"
                                  stroke-width="2" stroke-linejoin="round"
                                  stroke-linecap="round"></path>
                            <path fill="none"
                                  d="M -10 212.2646669470343 L 0 212.2646669470343 C 0 212.2646669470343 15.6345465417396 212.17543358772798 26.057577569566 212.17543358772798 C 36.48060859739199 212.17543358772798 41.692124111305 212.17543358772798 52.115155139131 212.19957737111088 C 62.538186166957395 212.22372115449377 67.7497016808706 212.29534509906364 78.172732708697 212.4192609371524 C 88.5957637365222 212.5431767752411 93.8072792504348 212.62383080963198 104.23031027826 212.81915656155462 C 114.65334130608801 213.0144823134773 119.864856820002 213.1172476467008 130.28788784783 213.39588969676566 C 140.710918875654 213.6745317468304 145.922434389566 213.84059356871816 156.34546541739 214.21236681187872 C 166.76849644521798 214.58414005503946 171.98001195913199 214.7770149570616 182.40304298696 215.25475591256892 C 192.827516449192 215.732562982241 198.03975318030803 216.01321512873696 208.46422664254 216.6012368748273 C 218.88725767036803 217.18917725634802 224.09877318428198 217.50445548826943 234.52180421211 218.1946612315966 C 244.94483523993398 218.88486697492348 250.15635075384597 219.23903262626877 260.57938178167 220.05226559146237 C 271.002412809498 220.8654985566563 276.213928323412 221.31165165498945 286.63695935124 222.26082605756545 C 297.05999037906804 223.21000046014146 302.27150589298196 223.7169261814997 312.69453692081 224.79813760434234 C 323.117567948634 225.8793490271846 328.329083462546 226.45029362447914 338.75211449037 227.66688317177778 C 349.175145518198 228.88347271907688 354.386661032112 229.5221016163931 364.80969205994 230.8810853408368 C 375.232723087764 232.24006906527998 380.444238601676 232.95134349606164 390.8672696295 234.46180179399502 C 401.290300657328 235.97226009192897 406.501816171242 236.7648974015686 416.92484719907 238.43337683050515 C 427.34787822689395 240.10185625944106 432.559393740806 240.97625163830514 442.98242476863 242.80419893867617 C 453.40545579645806 244.63214623904793 458.616971310372 245.57812181317036 469.0400023382 247.57311333236208 C 479.46303336602807 249.5681048515538 484.674548879942 250.61665934326103 495.09757990777 252.77915653463486 C 505.52061093559405 254.94165372600787 510.732126449506 256.0582334918197 521.15515747733 258.38559928922916 C 531.578188505158 260.71296508663954 536.789704019072 261.9043947729788 547.2127350469 264.41598552168443 C 557.6372085091319 266.9279238472988 562.8494452402481 268.24632650361934 573.27391870248 270.9444219750293 C 583.696949730308 273.64214411096594 588.9084652442219 275.04234702616526 599.33149627205 277.90552954005096 C 609.7545272998739 280.76871205393553 614.9660428137861 282.208708019911 625.38907384161 285.2603345444551 C 635.812104869438 288.31196106900035 641.023620383352 289.9087630914804 651.44665141118 293.1636621627743 C 661.869682439004 296.4185612340669 667.081197952916 298.09247914417506 677.50422898074 301.5348299009213 C 687.927260008568 304.9771806576689 693.1387755224821 306.73284339308333 703.56180655031 310.37541594650895 C 713.9848375781341 314.0179884999332 719.196353092046 315.9053091735226 729.61938411987 319.74769266804606 C 740.042415147698 323.590076162571 755.67696168944 329.58733341912983 755.67696168944 329.58733341912983 L 765.67696168944 329.58733341912983"
                                  stroke-linejoin="round" stroke="rgba(192,192,192,0.0001)"
                                  stroke-width="22" visibility="visible" data-z-index="2"
                                  class="highcharts-tracker-line"></path>
                        </g>
                        <g data-z-index="0.1"
                           class="highcharts-markers highcharts-series-2 highcharts-spline-series  highcharts-tracker"
                           transform="translate(70,10) scale(1 1)"></g>
                        <g data-z-index="0.1"
                           class="highcharts-series highcharts-series-3 highcharts-scatter-series  highcharts-tracker"
                           transform="translate(70,10) scale(1 1)"
                           clip-path="url(#highcharts-6mh5h5f-1985)"></g>
                        <g data-z-index="0.1"
                           class="highcharts-markers highcharts-series-3 highcharts-scatter-series  highcharts-tracker"
                           transform="translate(70,10) scale(1 1)">
                            <image preserveAspectRatio="none"
                                   xlink:href="https://wiseselector.flopo.com.br/images/point.png"
                                   x="540" y="91.25" width="20" transform="translate(-10,-10)"
                                   height="20" fill="black" class="highcharts-point"></image>
                        </g>
                        <g data-z-index="0.1"
                           class="highcharts-series highcharts-series-4 highcharts-spline-series "
                           transform="translate(70,10) scale(1 1)"
                           clip-path="url(#highcharts-6mh5h5f-1985)">
                            <path fill="none"
                                  d="M 0 365 C 0 365 19.1136983323728 340.1946427323053 31.856163887288 326.5866833534227 C 44.5971870077956 312.9802643819865 50.9676985680494 309.45192430132624 63.708721688557 296.964054124203 C 76.45118724347219 284.4747701725775 82.8224200209298 275.91322063859866 95.564885575845 264.14379803155083 C 108.305908696351 252.37570771141964 114.676420256604 248.36453561598378 127.41744337711 238.12027180625546 C 140.159908932026 227.8748482247816 146.53114170948402 222.35051985497907 159.2736072644 212.91957955354542 C 172.014630384908 203.48970682515966 178.38514194516202 199.3251613424624 191.12616506567 190.9682392317069 C 203.868630620586 182.61037101859495 210.239863398044 178.6731672323085 222.98232895296 171.1326037438768 C 235.723352073468 163.59289383972083 242.093863633722 160.02535925542986 254.83488675423 153.2675557502377 C 267.577352309146 146.50898718181583 273.948585086604 143.36026241206778 286.69105064152 137.3416735598417 C 299.432073762028 131.32376600587858 305.80258532228197 128.5258357669175 318.54360844279 123.17631473476473 C 331.286073997702 117.8261880736049 337.657306775158 115.34981653039299 350.39977233007 110.59255432656016 C 363.140795450578 105.83583064006858 369.511307010832 103.54654957737199 382.25233013134 99.39135000895374 C 394.994795686256 95.23568002283251 401.366028463714 93.40254792698381 414.10849401863 89.81538044021147 C 426.850959573546 86.22821295343913 433.222192351004 84.57196300942039 445.96465790592 81.45551257509203 C 458.705681026428 78.33941491984852 465.076192586682 76.93199291811844 477.81721570719 74.23401021628183 C 490.559681262106 71.53572207091493 496.93091403956396 70.31477791200427 509.67337959448 67.96483545708327 C 522.414402714988 65.61515901330738 528.784914275242 64.44401819752946 541.52593739575 62.484962969539595 C 554.268402950662 60.525685953343746 560.639635728118 59.726020050731215 573.38210128303 58.169004846618975 C 586.123124403538 56.61216589507641 592.493635963792 55.92201187033313 605.2346590843 54.700327580402586 C 617.977124639216 53.478504981370904 624.3483574166739 52.96769777690279 637.09082297159 52.060237624213414 C 649.831846092098 51.152880195109404 656.2023576523519 50.76029439513268 668.94338077286 50.16328362591912 C 681.6858463277761 49.5662052680302 688.0570791052339 49.42776227750982 700.79954466015 49.075014806457204 C 713.5405677806581 48.72230726606694 719.911079340912 48.43354580659462 732.65210246142 48.399646097311916 C 745.394568016336 48.36574638802921 751.765800793794 48.36574638802921 764.50826634871 48.36574638802921 C 777.249289469218 48.36574638802921 783.619801029472 48.78898020988594 796.36082414998 49.279959794090075 C 809.103289704892 49.77099496298605 815.474522482348 50.05440657597616 828.21698803726 50.820783270779486 C 840.9580111577679 51.5870732125046 847.328522718022 52.07281846449755 860.06954583853 53.11162638541117 C 872.8120113934459 54.15055191165948 879.1832441709039 54.69006337035734 891.92570972582 56.015116888684304 C 904.6681752807359 57.34017040701126 923.78187361311 59.73689397704595 923.78187361311 59.73689397704595"
                                  class="highcharts-graph" data-z-index="1" stroke="#5ef983"
                                  stroke-width="2" stroke-linejoin="round"
                                  stroke-linecap="round"></path>
                            <path fill="none"
                                  d="M -10 365 L 0 365 C 0 365 19.1136983323728 340.1946427323053 31.856163887288 326.5866833534227 C 44.5971870077956 312.9802643819865 50.9676985680494 309.45192430132624 63.708721688557 296.964054124203 C 76.45118724347219 284.4747701725775 82.8224200209298 275.91322063859866 95.564885575845 264.14379803155083 C 108.305908696351 252.37570771141964 114.676420256604 248.36453561598378 127.41744337711 238.12027180625546 C 140.159908932026 227.8748482247816 146.53114170948402 222.35051985497907 159.2736072644 212.91957955354542 C 172.014630384908 203.48970682515966 178.38514194516202 199.3251613424624 191.12616506567 190.9682392317069 C 203.868630620586 182.61037101859495 210.239863398044 178.6731672323085 222.98232895296 171.1326037438768 C 235.723352073468 163.59289383972083 242.093863633722 160.02535925542986 254.83488675423 153.2675557502377 C 267.577352309146 146.50898718181583 273.948585086604 143.36026241206778 286.69105064152 137.3416735598417 C 299.432073762028 131.32376600587858 305.80258532228197 128.5258357669175 318.54360844279 123.17631473476473 C 331.286073997702 117.8261880736049 337.657306775158 115.34981653039299 350.39977233007 110.59255432656016 C 363.140795450578 105.83583064006858 369.511307010832 103.54654957737199 382.25233013134 99.39135000895374 C 394.994795686256 95.23568002283251 401.366028463714 93.40254792698381 414.10849401863 89.81538044021147 C 426.850959573546 86.22821295343913 433.222192351004 84.57196300942039 445.96465790592 81.45551257509203 C 458.705681026428 78.33941491984852 465.076192586682 76.93199291811844 477.81721570719 74.23401021628183 C 490.559681262106 71.53572207091493 496.93091403956396 70.31477791200427 509.67337959448 67.96483545708327 C 522.414402714988 65.61515901330738 528.784914275242 64.44401819752946 541.52593739575 62.484962969539595 C 554.268402950662 60.525685953343746 560.639635728118 59.726020050731215 573.38210128303 58.169004846618975 C 586.123124403538 56.61216589507641 592.493635963792 55.92201187033313 605.2346590843 54.700327580402586 C 617.977124639216 53.478504981370904 624.3483574166739 52.96769777690279 637.09082297159 52.060237624213414 C 649.831846092098 51.152880195109404 656.2023576523519 50.76029439513268 668.94338077286 50.16328362591912 C 681.6858463277761 49.5662052680302 688.0570791052339 49.42776227750982 700.79954466015 49.075014806457204 C 713.5405677806581 48.72230726606694 719.911079340912 48.43354580659462 732.65210246142 48.399646097311916 C 745.394568016336 48.36574638802921 751.765800793794 48.36574638802921 764.50826634871 48.36574638802921 C 777.249289469218 48.36574638802921 783.619801029472 48.78898020988594 796.36082414998 49.279959794090075 C 809.103289704892 49.77099496298605 815.474522482348 50.05440657597616 828.21698803726 50.820783270779486 C 840.9580111577679 51.5870732125046 847.328522718022 52.07281846449755 860.06954583853 53.11162638541117 C 872.8120113934459 54.15055191165948 879.1832441709039 54.69006337035734 891.92570972582 56.015116888684304 C 904.6681752807359 57.34017040701126 923.78187361311 59.73689397704595 923.78187361311 59.73689397704595 L 933.78187361311 59.73689397704595"
                                  stroke-linejoin="round" stroke="rgba(192,192,192,0.0001)"
                                  stroke-width="22" visibility="visible" data-z-index="2"
                                  class="highcharts-tracker-line"></path>
                        </g>
                        <g data-z-index="0.1"
                           class="highcharts-markers highcharts-series-4 highcharts-spline-series  highcharts-tracker"
                           transform="translate(70,10) scale(1 1)"></g>
                    </g>
                    <text x="558" text-anchor="middle" class="highcharts-title" data-z-index="4"
                          style="color:#333333;font-size:18px;fill:#333333;" y="24"></text>
                    <text x="558" text-anchor="middle" class="highcharts-subtitle"
                          data-z-index="4" style="color:#666666;fill:#666666;" y="24"></text>
                    <g data-z-index="6"
                       class="highcharts-data-labels highcharts-series-0 highcharts-spline-series "
                       transform="translate(70,10) scale(1 1)" opacity="1" visibility="visible">
                        <g class="highcharts-label highcharts-data-label highcharts-data-label-color-undefined "
                           data-z-index="1" transform="translate(44,7)">
                            <text x="5" data-z-index="1"
                                  style="font-size:11px;font-weight:bold;color:#000000;fill:#000000;"
                                  y="16">
                                <tspan x="5" y="16" class="highcharts-text-outline"
                                       fill="#FFFFFF" stroke="#FFFFFF" stroke-width="2px"
                                       stroke-linejoin="round" style="">18.03
                                </tspan>
                                <tspan x="5" y="16">18.03</tspan>
                            </text>
                        </g>
                    </g>
                    <g data-z-index="6"
                       class="highcharts-data-labels highcharts-series-1 highcharts-spline-series "
                       transform="translate(70,10) scale(1 1)" opacity="1" visibility="visible">
                        <g class="highcharts-label highcharts-data-label highcharts-data-label-color-undefined "
                           data-z-index="1" transform="translate(41,63)">
                            <text x="5" data-z-index="1"
                                  style="font-size:11px;font-weight:bold;color:#000000;fill:#000000;"
                                  y="16">
                                <tspan x="5" y="16" class="highcharts-text-outline"
                                       fill="#FFFFFF" stroke="#FFFFFF" stroke-width="2px"
                                       stroke-linejoin="round">17.39
                                </tspan>
                                <tspan x="5" y="16">17.39</tspan>
                            </text>
                        </g>
                    </g>
                    <g data-z-index="6"
                       class="highcharts-data-labels highcharts-series-2 highcharts-spline-series "
                       transform="translate(70,10) scale(1 1)" opacity="1" visibility="visible">
                        <g class="highcharts-label highcharts-data-label highcharts-data-label-color-undefined "
                           data-z-index="1" transform="translate(30,219)">
                            <text x="5" data-z-index="1"
                                  style="font-size:11px;font-weight:bold;color:#000000;fill:#000000;"
                                  y="16">
                                <tspan x="5" y="16" class="highcharts-text-outline"
                                       fill="#FFFFFF" stroke="#FFFFFF" stroke-width="2px"
                                       stroke-linejoin="round">14.49
                                </tspan>
                                <tspan x="5" y="16">14.49</tspan>
                            </text>
                        </g>
                    </g>
                    <g class="highcharts-axis-labels highcharts-xaxis-labels "
                       data-z-index="7"></g>
                    <g class="highcharts-axis-labels highcharts-yaxis-labels " data-z-index="7">
                        <text x="55"
                              style="color:#666666;cursor:default;font-size:11px;fill:#666666;"
                              text-anchor="end" transform="translate(0,0)" y="380" opacity="1">
                            120
                        </text>
                        <text x="55"
                              style="color:#666666;cursor:default;font-size:11px;fill:#666666;"
                              text-anchor="end" transform="translate(0,0)" y="334" opacity="1">
                            150
                        </text>
                        <text x="55"
                              style="color:#666666;cursor:default;font-size:11px;fill:#666666;"
                              text-anchor="end" transform="translate(0,0)" y="288" opacity="1">
                            180
                        </text>
                        <text x="55"
                              style="color:#666666;cursor:default;font-size:11px;fill:#666666;"
                              text-anchor="end" transform="translate(0,0)" y="243" opacity="1">
                            210
                        </text>
                        <text x="55"
                              style="color:#666666;cursor:default;font-size:11px;fill:#666666;"
                              text-anchor="end" transform="translate(0,0)" y="197" opacity="1">
                            240
                        </text>
                        <text x="55"
                              style="color:#666666;cursor:default;font-size:11px;fill:#666666;"
                              text-anchor="end" transform="translate(0,0)" y="151" opacity="1">
                            270
                        </text>
                        <text x="55"
                              style="color:#666666;cursor:default;font-size:11px;fill:#666666;"
                              text-anchor="end" transform="translate(0,0)" y="106" opacity="1">
                            300
                        </text>
                        <text x="55"
                              style="color:#666666;cursor:default;font-size:11px;fill:#666666;"
                              text-anchor="end" transform="translate(0,0)" y="60" opacity="1">
                            330
                        </text>
                        <text x="55"
                              style="color:#666666;cursor:default;font-size:11px;fill:#666666;"
                              text-anchor="end" transform="translate(0,0)" y="15" opacity="1">
                            360
                        </text>
                    </g>
                    <g class="highcharts-axis-labels highcharts-yaxis-labels "
                       data-z-index="7"></g>
                    <g class="highcharts-axis-labels highcharts-yaxis-labels " data-z-index="7">
                        <text x="1080"
                              style="color:#666666;cursor:default;font-size:11px;fill:#666666;"
                              text-anchor="start" transform="translate(0,0)" y="380"
                              opacity="1">0
                        </text>
                        <text x="1080"
                              style="color:#666666;cursor:default;font-size:11px;fill:#666666;"
                              text-anchor="start" transform="translate(0,0)" y="136"
                              opacity="1">0.6
                        </text>
                        <text x="1080"
                              style="color:#666666;cursor:default;font-size:11px;fill:#666666;"
                              text-anchor="start" transform="translate(0,0)" y="319"
                              opacity="1">0.15
                        </text>
                        <text x="1080"
                              style="color:#666666;cursor:default;font-size:11px;fill:#666666;"
                              text-anchor="start" transform="translate(0,0)" y="258"
                              opacity="1">0.3
                        </text>
                        <text x="1080"
                              style="color:#666666;cursor:default;font-size:11px;fill:#666666;"
                              text-anchor="start" transform="translate(0,0)" y="197"
                              opacity="1">0.45
                        </text>
                        <text x="1080"
                              style="color:#666666;cursor:default;font-size:11px;fill:#666666;"
                              text-anchor="start" transform="translate(0,0)" y="75" opacity="1">
                            0.75
                        </text>
                        <text x="1080"
                              style="color:#666666;cursor:default;font-size:11px;fill:#666666;"
                              text-anchor="start" transform="translate(0,0)" y="15" opacity="1">
                            0.9
                        </text>
                    </g>
                    <g class="highcharts-axis-labels highcharts-yaxis-labels "
                       data-z-index="7"></g>
                    <g class="highcharts-axis-labels highcharts-yaxis-labels "
                       data-z-index="7"></g>
                </svg>
            </div>
            <div class="svg-wrap">
                <svg version="1.1" class="highcharts-root"
                     style="font-family:&quot;Lucida Grande&quot;, &quot;Lucida Sans Unicode&quot;, Arial, Helvetica, sans-serif;font-size:12px;"
                     xmlns="http://www.w3.org/2000/svg" width="1010" height="150"
                     viewBox="0 0 1010 150">
                    <desc>Created with Highcharts 6.2.0</desc>
                    <defs>
                        <clipPath id="highcharts-6mh5h5f-2112">
                            <rect x="0" y="0" width="930" height="85" fill="none"></rect>
                        </clipPath>
                    </defs>
                    <rect fill="#ffffff" class="highcharts-background" x="0" y="0" width="1010"
                          height="150" rx="0" ry="0"></rect>
                    <rect fill="none" class="highcharts-plot-background" x="70" y="10"
                          width="930" height="85"></rect>
                    <g class="highcharts-grid highcharts-xaxis-grid " data-z-index="1">
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 69.5 10 L 69.5 95"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 159.5 10 L 159.5 95"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 249.5 10 L 249.5 95"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 339.5 10 L 339.5 95"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 428.5 10 L 428.5 95"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 518.5 10 L 518.5 95"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 608.5 10 L 608.5 95"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 698.5 10 L 698.5 95"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 788.5 10 L 788.5 95"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 878.5 10 L 878.5 95"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 968.5 10 L 968.5 95"
                              opacity="1"></path>
                    </g>
                    <g class="highcharts-grid highcharts-yaxis-grid " data-z-index="1">
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 70 95.5 L 1000 95.5"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 70 53.5 L 1000 53.5"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 70 9.5 L 1000 9.5"
                              opacity="1"></path>
                    </g>
                    <g class="highcharts-grid highcharts-yaxis-grid " data-z-index="1"></g>
                    <rect fill="none" class="highcharts-plot-border" data-z-index="1" x="70"
                          y="10" width="930" height="85"></rect>
                    <g class="highcharts-axis highcharts-xaxis " data-z-index="2">
                        <path fill="none" class="highcharts-tick" stroke="#ccd6eb"
                              stroke-width="1" d="M 69.5 95 L 69.5 105" opacity="1"></path>
                        <path fill="none" class="highcharts-tick" stroke="#ccd6eb"
                              stroke-width="1" d="M 159.5 95 L 159.5 105" opacity="1"></path>
                        <path fill="none" class="highcharts-tick" stroke="#ccd6eb"
                              stroke-width="1" d="M 249.5 95 L 249.5 105" opacity="1"></path>
                        <path fill="none" class="highcharts-tick" stroke="#ccd6eb"
                              stroke-width="1" d="M 339.5 95 L 339.5 105" opacity="1"></path>
                        <path fill="none" class="highcharts-tick" stroke="#ccd6eb"
                              stroke-width="1" d="M 428.5 95 L 428.5 105" opacity="1"></path>
                        <path fill="none" class="highcharts-tick" stroke="#ccd6eb"
                              stroke-width="1" d="M 518.5 95 L 518.5 105" opacity="1"></path>
                        <path fill="none" class="highcharts-tick" stroke="#ccd6eb"
                              stroke-width="1" d="M 608.5 95 L 608.5 105" opacity="1"></path>
                        <path fill="none" class="highcharts-tick" stroke="#ccd6eb"
                              stroke-width="1" d="M 698.5 95 L 698.5 105" opacity="1"></path>
                        <path fill="none" class="highcharts-tick" stroke="#ccd6eb"
                              stroke-width="1" d="M 788.5 95 L 788.5 105" opacity="1"></path>
                        <path fill="none" class="highcharts-tick" stroke="#ccd6eb"
                              stroke-width="1" d="M 878.5 95 L 878.5 105" opacity="1"></path>
                        <path fill="none" class="highcharts-tick" stroke="#ccd6eb"
                              stroke-width="1" d="M 968.5 95 L 968.5 105" opacity="1"></path>
                        <text x="535" data-z-index="7" text-anchor="middle"
                              transform="translate(0,0)" class="highcharts-axis-title"
                              style="color:#666666;fill:#666666;" y="133">
                            <tspan>Flow - gal/min</tspan>
                        </text>
                        <path fill="none" class="highcharts-axis-line" stroke="#ccd6eb"
                              stroke-width="1" data-z-index="7"
                              d="M 70 95.5 L 1000 95.5"></path>
                    </g>
                    <g class="highcharts-axis highcharts-yaxis " data-z-index="2">
                        <text x="29.015625" data-z-index="7" text-anchor="middle"
                              transform="translate(0,0) rotate(270 29.015625 52.5)"
                              class="highcharts-axis-title" style="color:#666666;fill:#666666;"
                              y="52.5">
                            <tspan>NPSH - ft</tspan>
                        </text>
                        <path fill="none" class="highcharts-axis-line" stroke="#ccd6eb"
                              stroke-width="1" data-z-index="7" d="M 69.5 10 L 69.5 95"></path>
                    </g>
                    <g class="highcharts-axis highcharts-yaxis " data-z-index="2">
                        <path fill="none" class="highcharts-axis-line" stroke="#ccd6eb"
                              stroke-width="1" data-z-index="7"
                              d="M 1000.5 10 L 1000.5 95"></path>
                    </g>
                    <g class="highcharts-series-group" data-z-index="3">
                        <g data-z-index="0.1"
                           class="highcharts-series highcharts-series-0 highcharts-spline-series highcharts-color-0 "
                           transform="translate(70,10) scale(1 1)"
                           clip-path="url(#highcharts-6mh5h5f-2112)">
                            <path fill="none"
                                  d="M 0 59.36534243947881 C 0 59.36534243947881 19.051837377997202 63.651769638204016 31.753062296662 64.42006256402188 C 44.4528494493184 65.18835548983974 50.8027430256466 64.91773111218284 63.502530178303 65.18835548983974 C 76.2037550969678 65.45901050537478 82.5543675563002 65.56647306277404 95.255592474965 65.77326104700174 C 107.955379627623 65.98002562303564 114.305273203952 66.06485963629594 127.00506035661 66.22223689049373 C 139.706285275274 66.37963196165676 146.056897734606 66.45307538132553 158.75812265327 66.56019186040379 C 171.45790980592602 66.66729621400333 177.807803382254 66.70809831138023 190.50759053491 66.75778897218824 C 203.208815453574 66.80748525856636 209.559427912906 66.80865922836914 222.26065283157 66.80865922836914 C 234.960439984226 66.80865922836914 241.310333560554 66.80865922836914 254.01012071321 66.78745098925111 C 266.711345631874 66.76624275013309 273.061958091206 66.72668607309434 285.76318300987 66.64477411186327 C 298.462970162526 66.56287142298461 304.812863738854 66.49918604292782 317.51265089151 66.3779143639768 C 330.21387581017797 66.25662895563835 336.564488269512 66.19689746229933 349.26571318818 66.03838139363958 C 361.965500340836 65.87988326884094 368.315393917164 65.79643865371455 381.01518106982 65.5853788803308 C 393.716405988484 65.37429521248613 400.067018447816 65.23983163767673 412.76824336648 64.98302279056853 C 425.469468285144 64.72621394346032 431.82008074447606 64.60450096203311 444.52130566314 64.30133464478982 C 457.22109281579594 63.998202645671626 463.570986392124 63.83493291660159 476.27077354478 63.46727699966478 C 488.97199846344404 63.09957945973275 495.32261092277605 62.88541025034453 508.02383584144 62.46295100261773 C 520.723622994096 62.04053957685693 527.073516570424 61.83143085467178 539.77330372308 61.355100315945805 C 552.474528641748 60.87871585097282 558.825141101082 60.6364415383442 571.52636601975 60.081163493370305 C 584.2261531724059 59.52594830531812 590.576046748734 59.21646579488311 603.27583390139 58.5788672333806 C 615.977058820054 57.941196488184964 622.3276712793861 57.616517225653084 635.02889619805 56.89299022662494 C 647.728683350706 56.16954513013231 654.078576927034 55.7818961971747 666.77836407969 54.961436994578676 C 679.4795889983541 54.14088490630368 685.830201457686 53.71137977938518 698.53142637635 52.79046199944739 C 711.231213529006 51.869648466484875 717.581107105334 51.39694237627 730.28089425799 50.35710871232789 C 742.9821191766539 49.31715732692495 749.332731635986 48.75282111107114 762.03395655465 47.590999376084795 C 774.733743707306 46.429309158161466 781.0836372836341 45.848785249015286 793.78342443629 44.5483288300537 C 806.4846493549579 43.24772518405463 812.835261814292 42.54484496760156 825.53648673296 41.088349213683166 C 838.236273885616 39.63201833363364 844.586167461944 38.882324902384156 857.2859546146 37.2662622451339 C 869.987179533264 35.65001663049014 876.3377919925961 34.804623472059006 889.03901691126 33.00757853394814 C 901.740241829924 31.210533595837266 920.79207920792 28.281037554579576 920.79207920792 28.281037554579576"
                                  class="highcharts-graph" data-z-index="1" stroke="#7cb5ec"
                                  stroke-width="2" stroke-linejoin="round"
                                  stroke-linecap="round"></path>
                            <path fill="none"
                                  d="M -10 59.36534243947881 L 0 59.36534243947881 C 0 59.36534243947881 19.051837377997202 63.651769638204016 31.753062296662 64.42006256402188 C 44.4528494493184 65.18835548983974 50.8027430256466 64.91773111218284 63.502530178303 65.18835548983974 C 76.2037550969678 65.45901050537478 82.5543675563002 65.56647306277404 95.255592474965 65.77326104700174 C 107.955379627623 65.98002562303564 114.305273203952 66.06485963629594 127.00506035661 66.22223689049373 C 139.706285275274 66.37963196165676 146.056897734606 66.45307538132553 158.75812265327 66.56019186040379 C 171.45790980592602 66.66729621400333 177.807803382254 66.70809831138023 190.50759053491 66.75778897218824 C 203.208815453574 66.80748525856636 209.559427912906 66.80865922836914 222.26065283157 66.80865922836914 C 234.960439984226 66.80865922836914 241.310333560554 66.80865922836914 254.01012071321 66.78745098925111 C 266.711345631874 66.76624275013309 273.061958091206 66.72668607309434 285.76318300987 66.64477411186327 C 298.462970162526 66.56287142298461 304.812863738854 66.49918604292782 317.51265089151 66.3779143639768 C 330.21387581017797 66.25662895563835 336.564488269512 66.19689746229933 349.26571318818 66.03838139363958 C 361.965500340836 65.87988326884094 368.315393917164 65.79643865371455 381.01518106982 65.5853788803308 C 393.716405988484 65.37429521248613 400.067018447816 65.23983163767673 412.76824336648 64.98302279056853 C 425.469468285144 64.72621394346032 431.82008074447606 64.60450096203311 444.52130566314 64.30133464478982 C 457.22109281579594 63.998202645671626 463.570986392124 63.83493291660159 476.27077354478 63.46727699966478 C 488.97199846344404 63.09957945973275 495.32261092277605 62.88541025034453 508.02383584144 62.46295100261773 C 520.723622994096 62.04053957685693 527.073516570424 61.83143085467178 539.77330372308 61.355100315945805 C 552.474528641748 60.87871585097282 558.825141101082 60.6364415383442 571.52636601975 60.081163493370305 C 584.2261531724059 59.52594830531812 590.576046748734 59.21646579488311 603.27583390139 58.5788672333806 C 615.977058820054 57.941196488184964 622.3276712793861 57.616517225653084 635.02889619805 56.89299022662494 C 647.728683350706 56.16954513013231 654.078576927034 55.7818961971747 666.77836407969 54.961436994578676 C 679.4795889983541 54.14088490630368 685.830201457686 53.71137977938518 698.53142637635 52.79046199944739 C 711.231213529006 51.869648466484875 717.581107105334 51.39694237627 730.28089425799 50.35710871232789 C 742.9821191766539 49.31715732692495 749.332731635986 48.75282111107114 762.03395655465 47.590999376084795 C 774.733743707306 46.429309158161466 781.0836372836341 45.848785249015286 793.78342443629 44.5483288300537 C 806.4846493549579 43.24772518405463 812.835261814292 42.54484496760156 825.53648673296 41.088349213683166 C 838.236273885616 39.63201833363364 844.586167461944 38.882324902384156 857.2859546146 37.2662622451339 C 869.987179533264 35.65001663049014 876.3377919925961 34.804623472059006 889.03901691126 33.00757853394814 C 901.740241829924 31.210533595837266 920.79207920792 28.281037554579576 920.79207920792 28.281037554579576 L 930.79207920792 28.281037554579576"
                                  stroke-linejoin="round" stroke="rgba(192,192,192,0.0001)"
                                  stroke-width="22" visibility="visible" data-z-index="2"
                                  class="highcharts-tracker-line"></path>
                        </g>
                        <g data-z-index="0.1"
                           class="highcharts-markers highcharts-series-0 highcharts-spline-series highcharts-color-0 highcharts-tracker"
                           transform="translate(70,10) scale(1 1)"></g>
                    </g>
                    <text x="505" text-anchor="middle" class="highcharts-title" data-z-index="4"
                          style="color:#333333;font-size:18px;fill:#333333;" y="24"></text>
                    <text x="505" text-anchor="middle" class="highcharts-subtitle"
                          data-z-index="4" style="color:#666666;fill:#666666;" y="24"></text>
                    <g class="highcharts-axis-labels highcharts-xaxis-labels " data-z-index="7">
                        <text x="70"
                              style="color:#666666;cursor:default;font-size:11px;fill:#666666;"
                              text-anchor="middle" transform="translate(0,0)" y="114"
                              opacity="1">0
                        </text>
                        <text x="159.86037552825"
                              style="color:#666666;cursor:default;font-size:11px;fill:#666666;"
                              text-anchor="middle" transform="translate(0,0)" y="114"
                              opacity="1">250
                        </text>
                        <text x="249.7207510565"
                              style="color:#666666;cursor:default;font-size:11px;fill:#666666;"
                              text-anchor="middle" transform="translate(0,0)" y="114"
                              opacity="1">500
                        </text>
                        <text x="339.58112658475"
                              style="color:#666666;cursor:default;font-size:11px;fill:#666666;"
                              text-anchor="middle" transform="translate(0,0)" y="114"
                              opacity="1">750
                        </text>
                        <text x="429.44150211299"
                              style="color:#666666;cursor:default;font-size:11px;fill:#666666;"
                              text-anchor="middle" transform="translate(0,0)" y="114"
                              opacity="1">1000
                        </text>
                        <text x="519.30187764124"
                              style="color:#666666;cursor:default;font-size:11px;fill:#666666;"
                              text-anchor="middle" transform="translate(0,0)" y="114"
                              opacity="1">1250
                        </text>
                        <text x="609.16225316949"
                              style="color:#666666;cursor:default;font-size:11px;fill:#666666;"
                              text-anchor="middle" transform="translate(0,0)" y="114"
                              opacity="1">1500
                        </text>
                        <text x="699.02262869774"
                              style="color:#666666;cursor:default;font-size:11px;fill:#666666;"
                              text-anchor="middle" transform="translate(0,0)" y="114"
                              opacity="1">1750
                        </text>
                        <text x="788.88300422599"
                              style="color:#666666;cursor:default;font-size:11px;fill:#666666;"
                              text-anchor="middle" transform="translate(0,0)" y="114"
                              opacity="1">2000
                        </text>
                        <text x="878.74337975424"
                              style="color:#666666;cursor:default;font-size:11px;fill:#666666;"
                              text-anchor="middle" transform="translate(0,0)" y="114"
                              opacity="1">2250
                        </text>
                        <text x="968.60375528249"
                              style="color:#666666;cursor:default;font-size:11px;fill:#666666;"
                              text-anchor="middle" transform="translate(0,0)" y="114"
                              opacity="1">2500
                        </text>
                    </g>
                    <g class="highcharts-axis-labels highcharts-yaxis-labels " data-z-index="7">
                        <text x="55"
                              style="color:#666666;cursor:default;font-size:11px;fill:#666666;"
                              text-anchor="end" transform="translate(0,0)" y="100" opacity="1">0
                        </text>
                        <text x="55"
                              style="color:#666666;cursor:default;font-size:11px;fill:#666666;"
                              text-anchor="end" transform="translate(0,0)" y="57" opacity="1">25
                        </text>
                        <text x="55"
                              style="color:#666666;cursor:default;font-size:11px;fill:#666666;"
                              text-anchor="end" transform="translate(0,0)" y="15" opacity="1">50
                        </text>
                    </g>
                    <g class="highcharts-axis-labels highcharts-yaxis-labels "
                       data-z-index="7"></g>
                </svg>
            </div>
        </div>
        <div class="ten page landscape">
            <div class="text-ac">
                <p><strong>Tag: 001</strong> - VCT - KX | Size: Bomba vertical VCT - Novo teste </p>
            </div>
            <table class="table text-al">
                <thead class="tStrong">Pump Information</thead>
                <tbody>
                <tr>
                    <th>Tag:</th>
                    <td>001</td>
                </tr>
                <tr>
                    <th>Quantity:</th>
                    <td></td>
                </tr>
                <tr>
                    <th>Line:</th>
                    <td>VCT - KX</td>
                </tr>
                <tr>
                    <th>Size:</th>
                    <td>Bomba vertical VCT - Novo teste</td>
                </tr>
                <tr>
                    <th>Service:</th>
                    <td></td>
                </tr>
                </tbody>
            </table>
            <table class="table text-al">
                <thead class="tStrong">Duty Conditions</thead>
                <tbody>
                <tr>
                    <th>
                        Flow:
                    </th>
                    <td>2303.20 gal/min</td>
                    <th>NPSHa:</th>
                    <td>40 ft</td>
                    <th>Liquid:</th>
                </tr>
                <tr>
                    <th>Head:</th>
                    <td>139.55 ft</td>
                    <th>Suction Pressure:</th>
                    <td>ft</td>
                    <th>Temperature:</th>
                    <td>(60/60/60) C</td>
                </tr>
                <tr>
                    <th>Frequency:</th>
                    <td> 60Hz/882 RPM</td>
                    <th>vapor Pressure:</th>
                    <td>(//) ft</td>
                    <th>Sphere Diameter Size:</th>
                </tr>
                <tr>
                    <th>Speed Criteria:</th>
                    <td>All Suitable Asyc Speed</td>
                    <th>Density:</th>
                    <td>(0/0/1) S.G.</td>
                    <th>Solids Con by Vol:</th>
                    <td>00</td>
                </tr>
                <tr>
                    <th>Pump Operation:</th>
                    <td>-</td>
                    <th>Viscosity:</th>
                    <td>1.22 cSt</td>
                    <th> Cq/Ch/Ce/Cn:</th>
                    <td>1.00/1.00/1.00/1.00</td>
                </tr>
                </tbody>
            </table>
            <table class="table text-al">
                <thead class="tStrong">Performance Details</thead>
                <tbody>
                <tr>
                    <th>Rated Flow: <span class="span">2303.2 gal/min (141.81%)</span></th>
                    <th>Differential Head (Hr):<span class="span">139.55 ft</span></th>
                    <th>Hydraulic Power:<span class="span">81.16 hp</span></th>
                    <th>NPSHr:<span class="span">44.64 ft</span></th>
                    <th>Dmax:<span class="span">13.25</span></th>
                </tr>
                <tr>
                    <th>Normal Flow: <span class="span">-</span></th>
                    <th>Shutoff Head:<span class="span">499.52 ft</span></th>
                    <th>Rated Efficiency:<span class="span">58.86%</span></th>
                    <th>NPSHa - NPSHr:<span class="span">-4.64 ft</span></th>
                    <th>Drated:<span class="span">12.40</span></th>
                </tr>
                <tr>
                    <th>BEP Flow @ Drated: <span class="span">1624.14</span></th>
                    <th>Head Rise to Shutoff: <span class="span">57.95 %</span></th>
                    <th>BHP: <span class="span">137.90 hp</span></th>
                    <th>NPSHa/NPSHr: <span class="span">0.90</span></th>
                    <th>Dmin: <span class="span">10.25</span></th>
                </tr>
                <tr>
                    <th>MCSF:<span class="span">489.73 gal/min</span></th>
                    <th>Hmax @ Dmax:<span class="span">499.52 ft</span></th>
                    <th>Pmax @ Drated:<span class="span"> 152.09 hp</span></th>
                    <th>Nss:<span class="span">2538.22 US Units</span></th>
                    <th>Stages Rated:<span class="span"> 11 </span></th>
                </tr>
                <tr>
                    <th>MCTF:<span class="span"> -</span></th>
                    <th>Head Ratio:<span class="span">46.46  %</span></th>
                    <th>Pmax @ Dmax:<span class="span">179.18 hp </span></th>
                    <th>Ns:<span class="span">2760.68 US Units</span></th>
                    <th>Stages Max:<span class="span"> 14 </span></th>
                </tr>
                </tbody>
            </table>
            <table class="table text-al">
                <thead class="tStrong">Performance Details</thead>
                <tbody>
                <tr>
                    <th>Bowl Length:<span class="span">15.19</span></th>
                    <th>Reynolds:<span class="span">0.00</span></th>
                    <th>Column Diameter:<span class="span">0.00</span></th>
                </tr>
                <tr>
                    <th>Column Length:<span class="span"> 	0</span></th>
                    <th>Friction Factor:<span class="span"> 	0.00</span></th>
                    <th>Minimum Submergence to Prevent Cavitation:<span class="span"> 	45.29 ft</span></th>
                </tr>
                <tr>
                    <th>Total Length:<span class="span"> 	15.19 ft </span></th>
                    <th>Head Loss:<span class="span"> 	0.00 	</span></th>
                    <th>Minimum Submergence to Prevent Vortexes:<span class="span"> 	2.97 ft</span></th>
                </tr>
                <tr>
                    <th>CAN Length:<span class="span"> 	0.00 	</span></th>
                    <th>Suction Diameter:<span class="span"> 	0.00</span></th>
                </tr>
                </tbody>
            </table>
        </div>


        <div class="page flex j-cc a-ic">
            <h1 class="h1">
                Performance<br/> Curves
            </h1>
        </div>


        <div class="page landscape">
            <div class="svg-wrap">
                <svg version="1.1" class="highcharts-root"
                     style="font-family:&quot;Lucida Grande&quot;, &quot;Lucida Sans Unicode&quot;, Arial, Helvetica, sans-serif;font-size:12px;"
                     xmlns="http://www.w3.org/2000/svg" width="1010" height="200"
                     viewBox="0 0 1010 200">
                    <desc>Created with Highcharts 6.2.0</desc>
                    <defs>
                        <clipPath id="highcharts-6mh5h5f-1951">
                            <rect x="0" y="0" width="930" height="165" fill="none"></rect>
                        </clipPath>
                    </defs>
                    <rect fill="#ffffff" class="highcharts-background" x="0" y="0" width="1010"
                          height="200" rx="0" ry="0"></rect>
                    <rect fill="none" class="highcharts-plot-background" x="70" y="10"
                          width="930" height="165"></rect>
                    <g class="highcharts-grid highcharts-xaxis-grid " data-z-index="1">
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 69.5 10 L 69.5 175"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 159.5 10 L 159.5 175"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 249.5 10 L 249.5 175"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 339.5 10 L 339.5 175"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 428.5 10 L 428.5 175"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 518.5 10 L 518.5 175"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 608.5 10 L 608.5 175"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 698.5 10 L 698.5 175"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 788.5 10 L 788.5 175"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 878.5 10 L 878.5 175"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 968.5 10 L 968.5 175"
                              opacity="1"></path>
                    </g>
                    <g class="highcharts-grid highcharts-yaxis-grid " data-z-index="1">
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 70 175.5 L 1000 175.5"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 70 120.5 L 1000 120.5"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 70 65.5 L 1000 65.5"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 70 9.5 L 1000 9.5"
                              opacity="1"></path>
                    </g>
                    <g class="highcharts-grid highcharts-yaxis-grid " data-z-index="1"></g>
                    <rect fill="none" class="highcharts-plot-border" data-z-index="1" x="70"
                          y="10" width="930" height="165"></rect>
                    <g class="highcharts-axis highcharts-xaxis " data-z-index="2">
                        <path fill="none" class="highcharts-tick" stroke="#ccd6eb"
                              stroke-width="1" d="M 69.5 175 L 69.5 185" opacity="1"></path>
                        <path fill="none" class="highcharts-tick" stroke="#ccd6eb"
                              stroke-width="1" d="M 159.5 175 L 159.5 185" opacity="1"></path>
                        <path fill="none" class="highcharts-tick" stroke="#ccd6eb"
                              stroke-width="1" d="M 249.5 175 L 249.5 185" opacity="1"></path>
                        <path fill="none" class="highcharts-tick" stroke="#ccd6eb"
                              stroke-width="1" d="M 339.5 175 L 339.5 185" opacity="1"></path>
                        <path fill="none" class="highcharts-tick" stroke="#ccd6eb"
                              stroke-width="1" d="M 428.5 175 L 428.5 185" opacity="1"></path>
                        <path fill="none" class="highcharts-tick" stroke="#ccd6eb"
                              stroke-width="1" d="M 518.5 175 L 518.5 185" opacity="1"></path>
                        <path fill="none" class="highcharts-tick" stroke="#ccd6eb"
                              stroke-width="1" d="M 608.5 175 L 608.5 185" opacity="1"></path>
                        <path fill="none" class="highcharts-tick" stroke="#ccd6eb"
                              stroke-width="1" d="M 698.5 175 L 698.5 185" opacity="1"></path>
                        <path fill="none" class="highcharts-tick" stroke="#ccd6eb"
                              stroke-width="1" d="M 788.5 175 L 788.5 185" opacity="1"></path>
                        <path fill="none" class="highcharts-tick" stroke="#ccd6eb"
                              stroke-width="1" d="M 878.5 175 L 878.5 185" opacity="1"></path>
                        <path fill="none" class="highcharts-tick" stroke="#ccd6eb"
                              stroke-width="1" d="M 968.5 175 L 968.5 185" opacity="1"></path>
                        <path fill="none" class="highcharts-axis-line" stroke="#ccd6eb"
                              stroke-width="1" data-z-index="7"
                              d="M 70 175.5 L 1000 175.5"></path>
                    </g>
                    <g class="highcharts-axis highcharts-yaxis " data-z-index="2">
                        <text x="23.015625" data-z-index="7" text-anchor="middle"
                              transform="translate(0,0) rotate(270 23.015625 92.5)"
                              class="highcharts-axis-title" style="color:#666666;fill:#666666;"
                              y="92.5">
                            <tspan>Power - hp</tspan>
                        </text>
                        <path fill="none" class="highcharts-axis-line" stroke="#ccd6eb"
                              stroke-width="1" data-z-index="7" d="M 69.5 10 L 69.5 175"></path>
                    </g>
                    <g class="highcharts-axis highcharts-yaxis " data-z-index="2">
                        <path fill="none" class="highcharts-axis-line" stroke="#ccd6eb"
                              stroke-width="1" data-z-index="7"
                              d="M 1000.5 10 L 1000.5 175"></path>
                    </g>
                    <g class="highcharts-series-group" data-z-index="3">
                        <g data-z-index="0.1"
                           class="highcharts-series highcharts-series-0 highcharts-spline-series highcharts-color-0 "
                           transform="translate(70,10) scale(1 1)"
                           clip-path="url(#highcharts-6mh5h5f-1951)">
                            <path fill="none"
                                  d="M 0 144.76749185358975 C 0 144.76749185358975 19.051837377997202 128.47712610308812 31.753062296662 123.08666396164986 C 44.4528494493184 117.6962018202116 50.8027430256466 118.2428301544742 63.502530178303 117.6962018202116 C 76.2037550969678 117.14957348594899 82.5543675563002 117.6962018202116 95.255592474965 117.14957348594899 C 107.955379627623 116.60294515168638 114.305273203952 115.29835820652448 127.00506035661 114.3145286438774 C 139.706285275274 113.3305877000958 146.056897734606 113.14209185155629 158.75812265327 112.23014721987732 C 171.45790980592602 111.31830581942219 177.807803382254 110.73824574650388 190.50759053491 109.75506356354214 C 203.208815453574 108.77177007273679 209.559427912906 108.29848889749503 222.26065283157 107.31395803545954 C 234.960439984226 106.32953862133684 241.310333560554 105.84202729771715 254.01012071321 104.83268787314663 C 266.711345631874 103.82323417942358 273.061958091206 103.29641313701507 285.76318300987 102.26697523972558 C 298.462970162526 101.23765387378056 304.812863738854 100.71979464157498 317.51265089151 99.68578971506035 C 330.21387581017797 98.65166772696652 336.564488269512 98.14236693846131 349.26571318818 97.09665795320446 C 361.965500340836 96.05106734116333 368.315393917164 95.52366585978274 381.01518106982 94.45754072181539 C 393.716405988484 93.3912948858816 400.067018447816 92.84215976493927 412.76824336648 91.7657305184516 C 425.469468285144 90.68930127196396 431.82008074447606 90.15588999524702 444.52130566314 89.07539448937708 C 457.22109281579594 87.99502129452202 463.570986392124 87.43993732151209 476.27077354478 86.36355876663913 C 488.97199846344404 85.28705835299175 495.32261092277605 84.73892334721175 508.02383584144 83.6931970680762 C 520.723622994096 82.64758916411371 527.073516570424 82.15994176531119 539.77330372308 81.13522330889404 C 552.474528641748 80.11038884223586 558.825141101082 79.59872555599586 571.52636601975 78.5693147603879 C 584.2261531724059 77.54002049305684 590.576046748734 77.01097860881644 603.27583390139 75.98846065154652 C 615.977058820054 74.9658269331584 622.3276712793861 74.45065909912064 635.02889619805 73.45643557124278 C 647.728683350706 72.46232458847783 654.078576927034 71.98356890175667 666.77836407969 71.01762437493947 C 679.4795889983541 70.05157049178509 685.830201457686 69.54807483481947 698.53142637635 68.62643954631382 C 711.231213529006 67.7049085860047 717.581107105334 67.27640078977346 730.28089425799 66.40970875290253 C 742.9821191766539 65.54291859624935 749.332731635986 65.13470060864074 762.03395655465 64.29273406250354 C 774.733743707306 63.4508628261406 781.0836372836341 63.01014882245455 793.78342443629 62.200114296652146 C 806.4846493549579 61.38998806536714 812.835261814292 61.00716216098411 825.53648673296 60.242332169785016 C 838.236273885616 59.47758875657926 844.586167461944 59.08954155120895 857.2859546146 58.37618078564003 C 869.987179533264 57.66273925920103 876.3377919925961 57.33887015089095 889.03901691126 56.675326439765215 C 901.740241829924 56.01178272863948 920.79207920792 55.05846223001137 920.79207920792 55.05846223001137"
                                  class="highcharts-graph" data-z-index="1" stroke="#7cb5ec"
                                  stroke-width="2" stroke-linejoin="round"
                                  stroke-linecap="round"></path>
                            <path fill="none"
                                  d="M -10 144.76749185358975 L 0 144.76749185358975 C 0 144.76749185358975 19.051837377997202 128.47712610308812 31.753062296662 123.08666396164986 C 44.4528494493184 117.6962018202116 50.8027430256466 118.2428301544742 63.502530178303 117.6962018202116 C 76.2037550969678 117.14957348594899 82.5543675563002 117.6962018202116 95.255592474965 117.14957348594899 C 107.955379627623 116.60294515168638 114.305273203952 115.29835820652448 127.00506035661 114.3145286438774 C 139.706285275274 113.3305877000958 146.056897734606 113.14209185155629 158.75812265327 112.23014721987732 C 171.45790980592602 111.31830581942219 177.807803382254 110.73824574650388 190.50759053491 109.75506356354214 C 203.208815453574 108.77177007273679 209.559427912906 108.29848889749503 222.26065283157 107.31395803545954 C 234.960439984226 106.32953862133684 241.310333560554 105.84202729771715 254.01012071321 104.83268787314663 C 266.711345631874 103.82323417942358 273.061958091206 103.29641313701507 285.76318300987 102.26697523972558 C 298.462970162526 101.23765387378056 304.812863738854 100.71979464157498 317.51265089151 99.68578971506035 C 330.21387581017797 98.65166772696652 336.564488269512 98.14236693846131 349.26571318818 97.09665795320446 C 361.965500340836 96.05106734116333 368.315393917164 95.52366585978274 381.01518106982 94.45754072181539 C 393.716405988484 93.3912948858816 400.067018447816 92.84215976493927 412.76824336648 91.7657305184516 C 425.469468285144 90.68930127196396 431.82008074447606 90.15588999524702 444.52130566314 89.07539448937708 C 457.22109281579594 87.99502129452202 463.570986392124 87.43993732151209 476.27077354478 86.36355876663913 C 488.97199846344404 85.28705835299175 495.32261092277605 84.73892334721175 508.02383584144 83.6931970680762 C 520.723622994096 82.64758916411371 527.073516570424 82.15994176531119 539.77330372308 81.13522330889404 C 552.474528641748 80.11038884223586 558.825141101082 79.59872555599586 571.52636601975 78.5693147603879 C 584.2261531724059 77.54002049305684 590.576046748734 77.01097860881644 603.27583390139 75.98846065154652 C 615.977058820054 74.9658269331584 622.3276712793861 74.45065909912064 635.02889619805 73.45643557124278 C 647.728683350706 72.46232458847783 654.078576927034 71.98356890175667 666.77836407969 71.01762437493947 C 679.4795889983541 70.05157049178509 685.830201457686 69.54807483481947 698.53142637635 68.62643954631382 C 711.231213529006 67.7049085860047 717.581107105334 67.27640078977346 730.28089425799 66.40970875290253 C 742.9821191766539 65.54291859624935 749.332731635986 65.13470060864074 762.03395655465 64.29273406250354 C 774.733743707306 63.4508628261406 781.0836372836341 63.01014882245455 793.78342443629 62.200114296652146 C 806.4846493549579 61.38998806536714 812.835261814292 61.00716216098411 825.53648673296 60.242332169785016 C 838.236273885616 59.47758875657926 844.586167461944 59.08954155120895 857.2859546146 58.37618078564003 C 869.987179533264 57.66273925920103 876.3377919925961 57.33887015089095 889.03901691126 56.675326439765215 C 901.740241829924 56.01178272863948 920.79207920792 55.05846223001137 920.79207920792 55.05846223001137 L 930.79207920792 55.05846223001137"
                                  stroke-linejoin="round" stroke="rgba(192,192,192,0.0001)"
                                  stroke-width="22" visibility="visible" data-z-index="2"
                                  class="highcharts-tracker-line"></path>
                        </g>
                        <g data-z-index="0.1"
                           class="highcharts-markers highcharts-series-0 highcharts-spline-series highcharts-color-0 highcharts-tracker"
                           transform="translate(70,10) scale(1 1)"></g>
                    </g>
                    <text x="505" text-anchor="middle" class="highcharts-title" data-z-index="4"
                          style="color:#333333;font-size:18px;fill:#333333;" y="24"></text>
                    <text x="505" text-anchor="middle" class="highcharts-subtitle"
                          data-z-index="4" style="color:#666666;fill:#666666;" y="24"></text>
                    <g class="highcharts-axis-labels highcharts-xaxis-labels "
                       data-z-index="7"></g>
                    <g class="highcharts-axis-labels highcharts-yaxis-labels " data-z-index="7">
                        <text x="55"
                              style="color:#666666;cursor:default;font-size:11px;fill:#666666;"
                              text-anchor="end" transform="translate(0,0)" y="180" opacity="1">0
                        </text>
                        <text x="55"
                              style="color:#666666;cursor:default;font-size:11px;fill:#666666;"
                              text-anchor="end" transform="translate(0,0)" y="125" opacity="1">
                            100
                        </text>
                        <text x="55"
                              style="color:#666666;cursor:default;font-size:11px;fill:#666666;"
                              text-anchor="end" transform="translate(0,0)" y="70" opacity="1">
                            200
                        </text>
                        <text x="55"
                              style="color:#666666;cursor:default;font-size:11px;fill:#666666;"
                              text-anchor="end" transform="translate(0,0)" y="15" opacity="1">
                            300
                        </text>
                    </g>
                    <g class="highcharts-axis-labels highcharts-yaxis-labels "
                       data-z-index="7"></g>
                </svg>
            </div>
            <div class="svg-wrap">
                <svg version="1.1" class="highcharts-root"
                     style="font-family:&quot;Lucida Grande&quot;, &quot;Lucida Sans Unicode&quot;, Arial, Helvetica, sans-serif;font-size:12px;"
                     xmlns="http://www.w3.org/2000/svg" width="1116" height="400"
                     viewBox="0 0 1116 400">
                    <desc>Created with Highcharts 6.2.0</desc>
                    <defs>
                        <clipPath id="highcharts-6mh5h5f-1985">
                            <rect x="0" y="0" width="971" height="365" fill="none"></rect>
                        </clipPath>
                    </defs>
                    <rect fill="#ffffff" class="highcharts-background" x="0" y="0" width="1116"
                          height="400" rx="0" ry="0"></rect>
                    <rect fill="none" class="highcharts-plot-background" x="70" y="10"
                          width="971" height="365"></rect>
                    <g class="highcharts-grid highcharts-xaxis-grid " data-z-index="1">
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 69.5 10 L 69.5 375"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 159.5 10 L 159.5 375"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 249.5 10 L 249.5 375"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 339.5 10 L 339.5 375"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 430.5 10 L 430.5 375"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 520.5 10 L 520.5 375"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 610.5 10 L 610.5 375"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 700.5 10 L 700.5 375"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 790.5 10 L 790.5 375"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 880.5 10 L 880.5 375"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 971.5 10 L 971.5 375"
                              opacity="1"></path>
                    </g>
                    <g class="highcharts-grid highcharts-yaxis-grid " data-z-index="1">
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 70 375.5 L 1041 375.5"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 70 329.5 L 1041 329.5"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 70 284.5 L 1041 284.5"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 70 238.5 L 1041 238.5"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 70 193.5 L 1041 193.5"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 70 147.5 L 1041 147.5"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 70 101.5 L 1041 101.5"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 70 56.5 L 1041 56.5"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 70 9.5 L 1041 9.5"
                              opacity="1"></path>
                    </g>
                    <g class="highcharts-grid highcharts-yaxis-grid " data-z-index="1"></g>
                    <g class="highcharts-grid highcharts-yaxis-grid " data-z-index="1">
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 70 375.5 L 1041 375.5"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 70 132.5 L 1041 132.5"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 70 314.5 L 1041 314.5"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 70 253.5 L 1041 253.5"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 70 193.5 L 1041 193.5"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 70 71.5 L 1041 71.5"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 70 9.5 L 1041 9.5"
                              opacity="1"></path>
                    </g>
                    <g class="highcharts-grid highcharts-yaxis-grid " data-z-index="1"></g>
                    <g class="highcharts-grid highcharts-yaxis-grid " data-z-index="1"></g>
                    <rect fill="none" class="highcharts-plot-border" data-z-index="1" x="70"
                          y="10" width="971" height="365"></rect>
                    <g class="highcharts-axis highcharts-xaxis " data-z-index="2">
                        <path fill="none" class="highcharts-tick" stroke="#ccd6eb"
                              stroke-width="1" d="M 69.5 375 L 69.5 385" opacity="1"></path>
                        <path fill="none" class="highcharts-tick" stroke="#ccd6eb"
                              stroke-width="1" d="M 159.5 375 L 159.5 385" opacity="1"></path>
                        <path fill="none" class="highcharts-tick" stroke="#ccd6eb"
                              stroke-width="1" d="M 249.5 375 L 249.5 385" opacity="1"></path>
                        <path fill="none" class="highcharts-tick" stroke="#ccd6eb"
                              stroke-width="1" d="M 339.5 375 L 339.5 385" opacity="1"></path>
                        <path fill="none" class="highcharts-tick" stroke="#ccd6eb"
                              stroke-width="1" d="M 430.5 375 L 430.5 385" opacity="1"></path>
                        <path fill="none" class="highcharts-tick" stroke="#ccd6eb"
                              stroke-width="1" d="M 520.5 375 L 520.5 385" opacity="1"></path>
                        <path fill="none" class="highcharts-tick" stroke="#ccd6eb"
                              stroke-width="1" d="M 610.5 375 L 610.5 385" opacity="1"></path>
                        <path fill="none" class="highcharts-tick" stroke="#ccd6eb"
                              stroke-width="1" d="M 700.5 375 L 700.5 385" opacity="1"></path>
                        <path fill="none" class="highcharts-tick" stroke="#ccd6eb"
                              stroke-width="1" d="M 790.5 375 L 790.5 385" opacity="1"></path>
                        <path fill="none" class="highcharts-tick" stroke="#ccd6eb"
                              stroke-width="1" d="M 880.5 375 L 880.5 385" opacity="1"></path>
                        <path fill="none" class="highcharts-tick" stroke="#ccd6eb"
                              stroke-width="1" d="M 971.5 375 L 971.5 385" opacity="1"></path>
                        <path fill="none" class="highcharts-axis-line" stroke="#ccd6eb"
                              stroke-width="1" data-z-index="7"
                              d="M 70 375.5 L 1041 375.5"></path>
                    </g>
                    <g class="highcharts-axis highcharts-yaxis " data-z-index="2">
                        <text x="23.015625" data-z-index="7" text-anchor="middle"
                              transform="translate(0,0) rotate(270 23.015625 192.5)"
                              class="highcharts-axis-title" style="color:#666666;fill:#666666;"
                              y="192.5">
                            <tspan>Head - ft</tspan>
                        </text>
                        <path fill="none" class="highcharts-axis-line" data-z-index="7"
                              d="M 70 10 L 70 375"></path>
                    </g>
                    <g class="highcharts-axis highcharts-yaxis " data-z-index="2">
                        <text x="1051" data-z-index="7" text-anchor="middle"
                              transform="translate(0,0) rotate(90 1051 192.5)"
                              class="highcharts-axis-title" style="color:#666666;fill:#666666;"
                              y="192.5">
                            <tspan>Efficiency %</tspan>
                        </text>
                        <path fill="none" class="highcharts-axis-line" stroke="#ccd6eb"
                              stroke-width="1" data-z-index="7"
                              d="M 1041.5 10 L 1041.5 375"></path>
                    </g>
                    <g class="highcharts-axis highcharts-yaxis " data-z-index="2">
                        <path fill="none" class="highcharts-axis-line" data-z-index="7"
                              d="M 1065 10 L 1065 375"></path>
                    </g>
                    <g class="highcharts-axis highcharts-yaxis " data-z-index="2">
                        <path fill="none" class="highcharts-axis-line" data-z-index="7"
                              d="M 1106 10 L 1106 375"></path>
                    </g>
                    <g class="highcharts-axis highcharts-yaxis " data-z-index="2">
                        <path fill="none" class="highcharts-axis-line" data-z-index="7"
                              d="M 1106 10 L 1106 375"></path>
                    </g>
                    <g class="highcharts-series-group" data-z-index="3">
                        <g data-z-index="0.1"
                           class="highcharts-series highcharts-series-0 highcharts-spline-series "
                           transform="translate(70,10) scale(1 1)"
                           clip-path="url(#highcharts-6mh5h5f-1985)">
                            <path fill="none"
                                  d="M 0 16.904724594987727 C 0 16.904724594987727 19.8904492607544 16.421227949654224 33.150748767924 16.421227949654224 C 46.4110482750932 16.421227949654224 53.04119802867781 16.65789904828049 66.301497535847 16.75006008174182 C 79.5617970430166 16.842221115203156 86.1919467966014 16.80718435796472 99.452246303771 16.882033116960883 C 112.7139882453466 16.956890017886657 119.34485921613441 16.899632201605606 132.60660115771 17.124324231546666 C 145.866900664882 17.34899182250259 152.497050418468 17.67052405077241 165.75734992564 18.005432169203345 C 179.017649432808 18.340340287634177 185.647799186392 18.329298270102402 198.90809869356 18.79886482370108 C 212.168398200728 19.268431377299763 218.79854795431203 19.714908760628514 232.05884746148 20.35326493719674 C 245.319146968652 20.99162111376516 251.94929672223802 21.3233552731331 265.20959622941 21.990645706542693 C 278.469895736578 22.657936139952085 285.100045490162 22.88150629902967 298.36034499733 23.68971710424421 C 311.62064450450197 24.497927909458994 318.250794258088 24.991784560243513 331.51109376526 26.031699732616005 C 344.77283570683596 27.071728025315906 351.403706677624 27.76035091381759 364.6654486192 28.88957576692519 C 377.9257481263679 30.01867779809961 384.555897879952 30.417982333114104 397.81619738712 31.677516943321052 C 411.076496894292 32.937051553528384 417.706646647878 33.69864178872074 430.96694615505 35.18724881796089 C 444.22724566221797 36.675855847200594 450.857395415802 37.5008101441869 464.11769492297 39.120552089520686 C 477.377994430138 40.740294034854486 484.00814418372204 41.52687338200739 497.26844369089 43.285958544629864 C 510.528743198062 45.045043707252866 517.1588929516481 45.916969443756564 530.41919245882 47.91597790263438 C 543.6794919659881 49.91498636151162 550.309641719572 51.00221134013895 563.56994122674 53.28100083901751 C 576.831683168316 55.56003822101365 583.462554139104 56.88328161838885 596.72429608068 59.31054510482113 C 609.984595587852 61.73754458608909 616.614745341438 62.865343660295295 629.87504484861 65.41665825826811 C 643.135344355778 67.9679728562402 649.7654941093621 69.27119638117874 663.02579361653 72.0671180946834 C 676.286093123698 74.86303980818806 682.9162428772821 76.36388452547419 696.17654238445 79.39626682579143 C 709.4368418916221 82.4286491261096 716.066991645208 83.98418203938404 729.32729115238 87.22902959627191 C 742.587590659548 90.47387715315881 749.217740413132 92.15924452188898 762.4780399203 95.62050461022835 C 775.7383394274681 99.08176469856772 782.3684891810519 100.85372374376443 795.62878868822 104.53533003796878 C 808.8905306298 108.21733681148409 815.52140160059 110.10722695644235 828.78314354217 114.02953727952749 C 842.0434430493381 117.95142098630465 848.673592802922 119.98470997287545 861.93389231009 124.14581511262458 C 875.1941918172579 128.3069202523737 881.8243415708421 130.43261705026373 895.08464107801 134.83506297827302 C 908.3449405851819 139.23750890628364 914.9750903387679 141.51683178164177 928.23538984594 146.15804475267436 C 941.495689353108 150.79925772370558 961.38613861386 158.04112783343254 961.38613861386 158.04112783343254"
                                  class="highcharts-graph" data-z-index="1" stroke="black"
                                  stroke-width="2" stroke-linejoin="round"
                                  stroke-linecap="round"></path>
                            <path fill="none"
                                  d="M -10 16.904724594987727 L 0 16.904724594987727 C 0 16.904724594987727 19.8904492607544 16.421227949654224 33.150748767924 16.421227949654224 C 46.4110482750932 16.421227949654224 53.04119802867781 16.65789904828049 66.301497535847 16.75006008174182 C 79.5617970430166 16.842221115203156 86.1919467966014 16.80718435796472 99.452246303771 16.882033116960883 C 112.7139882453466 16.956890017886657 119.34485921613441 16.899632201605606 132.60660115771 17.124324231546666 C 145.866900664882 17.34899182250259 152.497050418468 17.67052405077241 165.75734992564 18.005432169203345 C 179.017649432808 18.340340287634177 185.647799186392 18.329298270102402 198.90809869356 18.79886482370108 C 212.168398200728 19.268431377299763 218.79854795431203 19.714908760628514 232.05884746148 20.35326493719674 C 245.319146968652 20.99162111376516 251.94929672223802 21.3233552731331 265.20959622941 21.990645706542693 C 278.469895736578 22.657936139952085 285.100045490162 22.88150629902967 298.36034499733 23.68971710424421 C 311.62064450450197 24.497927909458994 318.250794258088 24.991784560243513 331.51109376526 26.031699732616005 C 344.77283570683596 27.071728025315906 351.403706677624 27.76035091381759 364.6654486192 28.88957576692519 C 377.9257481263679 30.01867779809961 384.555897879952 30.417982333114104 397.81619738712 31.677516943321052 C 411.076496894292 32.937051553528384 417.706646647878 33.69864178872074 430.96694615505 35.18724881796089 C 444.22724566221797 36.675855847200594 450.857395415802 37.5008101441869 464.11769492297 39.120552089520686 C 477.377994430138 40.740294034854486 484.00814418372204 41.52687338200739 497.26844369089 43.285958544629864 C 510.528743198062 45.045043707252866 517.1588929516481 45.916969443756564 530.41919245882 47.91597790263438 C 543.6794919659881 49.91498636151162 550.309641719572 51.00221134013895 563.56994122674 53.28100083901751 C 576.831683168316 55.56003822101365 583.462554139104 56.88328161838885 596.72429608068 59.31054510482113 C 609.984595587852 61.73754458608909 616.614745341438 62.865343660295295 629.87504484861 65.41665825826811 C 643.135344355778 67.9679728562402 649.7654941093621 69.27119638117874 663.02579361653 72.0671180946834 C 676.286093123698 74.86303980818806 682.9162428772821 76.36388452547419 696.17654238445 79.39626682579143 C 709.4368418916221 82.4286491261096 716.066991645208 83.98418203938404 729.32729115238 87.22902959627191 C 742.587590659548 90.47387715315881 749.217740413132 92.15924452188898 762.4780399203 95.62050461022835 C 775.7383394274681 99.08176469856772 782.3684891810519 100.85372374376443 795.62878868822 104.53533003796878 C 808.8905306298 108.21733681148409 815.52140160059 110.10722695644235 828.78314354217 114.02953727952749 C 842.0434430493381 117.95142098630465 848.673592802922 119.98470997287545 861.93389231009 124.14581511262458 C 875.1941918172579 128.3069202523737 881.8243415708421 130.43261705026373 895.08464107801 134.83506297827302 C 908.3449405851819 139.23750890628364 914.9750903387679 141.51683178164177 928.23538984594 146.15804475267436 C 941.495689353108 150.79925772370558 961.38613861386 158.04112783343254 961.38613861386 158.04112783343254 L 971.38613861386 158.04112783343254"
                                  stroke-linejoin="round" stroke="rgba(192,192,192,0.0001)"
                                  stroke-width="22" visibility="visible" data-z-index="2"
                                  class="highcharts-tracker-line"></path>
                        </g>
                        <g data-z-index="0.1"
                           class="highcharts-markers highcharts-series-0 highcharts-spline-series  highcharts-tracker"
                           transform="translate(70,10) scale(1 1)"></g>
                        <g data-z-index="0.1"
                           class="highcharts-series highcharts-series-1 highcharts-spline-series "
                           transform="translate(70,10) scale(1 1)"
                           clip-path="url(#highcharts-6mh5h5f-1985)">
                            <path fill="none"
                                  d="M 0 55.78433017358901 C 0 55.78433017358901 19.1136983323728 55.3888436102788 31.856163887288 55.3888436102788 C 44.5971870077956 55.3888436102788 50.9676985680494 55.56582921372388 63.708721688557 55.64893096744299 C 76.45118724347219 55.73204212926283 82.8224200209298 55.71636603578949 95.564885575845 55.80437589912617 C 108.305908696351 55.89237579983398 114.676420256604 55.86776773958907 127.41744337711 56.088955377554214 C 140.159908932026 56.310168056574305 146.53114170948402 56.58366893982341 159.2736072644 56.91037669158925 C 172.014630384908 57.237047460363016 178.38514194516202 57.26898446445267 191.12616506567 57.722401678903225 C 203.868630620586 58.17587022554156 210.239863398044 58.567833999698564 222.98232895296 59.17759109431148 C 235.723352073468 59.787279165028664 242.093863633722 60.11208575970241 254.83488675423 60.77101459222848 C 267.577352309146 61.43001802328652 273.948585086604 61.679560693221916 286.69105064152 62.47242175327176 C 299.432073762028 63.265193062239376 305.80258532228197 63.73322205496035 318.54360844279 64.73509551477213 C 331.286073997702 65.73708239850073 337.657306775158 66.37788695976329 350.39977233007 67.48207261212269 C 363.140795450578 68.5861332717665 369.511307010832 69.01858415844288 382.25233013134 70.25571129478016 C 394.994795686256 71.49297848853134 401.366028463714 72.2207231735291 414.10849401863 73.66805843734386 C 426.850959573546 75.11539370115861 433.222192351004 75.90862668587096 445.96465790592 77.49238761385396 C 458.705681026428 79.07596926167751 465.076192586682 79.8578411794345 477.81721570719 81.58641487686026 C 490.559681262106 83.31518426925922 496.93091403956396 84.18273637533397 509.67337959448 86.13574533841575 C 522.414402714988 88.08853322282827 528.784914275242 89.14272425355006 541.52593739575 91.350906995596 C 554.268402950662 93.55933973002696 560.639635728118 94.81283364650271 573.38210128303 97.17728402960802 C 586.123124403538 99.54146675928592 592.493635963792 100.67050546697115 605.2346590843 103.17248977755406 C 617.977124639216 105.6747573423328 624.3483574166739 106.95567255859036 637.09082297159 109.68791371801211 C 649.831846092098 112.41984559045619 656.2023576523519 113.87223204151638 668.94338077286 116.83292235721868 C 681.6858463277761 119.79394785805817 688.0570791052339 121.32016257405654 700.79954466015 124.49220325936662 C 713.5405677806581 127.6638848728308 719.911079340912 129.31154177851383 732.65210246142 132.69222810415428 C 745.394568016336 136.07329716344438 751.765800793794 137.79707839803558 764.50826634871 141.39659172169297 C 777.249289469218 144.99569758402762 783.619801029472 146.851941370361 796.36082414998 150.68877606913432 C 809.103289704892 154.52604514294325 815.474522482348 156.51137486552912 828.21698803726 160.58185115314856 C 840.9580111577679 164.65186666690812 847.328522718022 166.73110430513333 860.06954583853 171.04000557258183 C 872.8120113934459 175.34939465858224 879.1832441709039 177.58083033564742 891.92570972582 182.1275770367709 C 904.6681752807359 186.67432373789433 923.78187361311 193.77373907819916 923.78187361311 193.77373907819916"
                                  class="highcharts-graph" data-z-index="1" stroke="#24CBE5"
                                  stroke-width="2" stroke-linejoin="round"
                                  stroke-linecap="round"></path>
                            <path fill="none"
                                  d="M -10 55.78433017358901 L 0 55.78433017358901 C 0 55.78433017358901 19.1136983323728 55.3888436102788 31.856163887288 55.3888436102788 C 44.5971870077956 55.3888436102788 50.9676985680494 55.56582921372388 63.708721688557 55.64893096744299 C 76.45118724347219 55.73204212926283 82.8224200209298 55.71636603578949 95.564885575845 55.80437589912617 C 108.305908696351 55.89237579983398 114.676420256604 55.86776773958907 127.41744337711 56.088955377554214 C 140.159908932026 56.310168056574305 146.53114170948402 56.58366893982341 159.2736072644 56.91037669158925 C 172.014630384908 57.237047460363016 178.38514194516202 57.26898446445267 191.12616506567 57.722401678903225 C 203.868630620586 58.17587022554156 210.239863398044 58.567833999698564 222.98232895296 59.17759109431148 C 235.723352073468 59.787279165028664 242.093863633722 60.11208575970241 254.83488675423 60.77101459222848 C 267.577352309146 61.43001802328652 273.948585086604 61.679560693221916 286.69105064152 62.47242175327176 C 299.432073762028 63.265193062239376 305.80258532228197 63.73322205496035 318.54360844279 64.73509551477213 C 331.286073997702 65.73708239850073 337.657306775158 66.37788695976329 350.39977233007 67.48207261212269 C 363.140795450578 68.5861332717665 369.511307010832 69.01858415844288 382.25233013134 70.25571129478016 C 394.994795686256 71.49297848853134 401.366028463714 72.2207231735291 414.10849401863 73.66805843734386 C 426.850959573546 75.11539370115861 433.222192351004 75.90862668587096 445.96465790592 77.49238761385396 C 458.705681026428 79.07596926167751 465.076192586682 79.8578411794345 477.81721570719 81.58641487686026 C 490.559681262106 83.31518426925922 496.93091403956396 84.18273637533397 509.67337959448 86.13574533841575 C 522.414402714988 88.08853322282827 528.784914275242 89.14272425355006 541.52593739575 91.350906995596 C 554.268402950662 93.55933973002696 560.639635728118 94.81283364650271 573.38210128303 97.17728402960802 C 586.123124403538 99.54146675928592 592.493635963792 100.67050546697115 605.2346590843 103.17248977755406 C 617.977124639216 105.6747573423328 624.3483574166739 106.95567255859036 637.09082297159 109.68791371801211 C 649.831846092098 112.41984559045619 656.2023576523519 113.87223204151638 668.94338077286 116.83292235721868 C 681.6858463277761 119.79394785805817 688.0570791052339 121.32016257405654 700.79954466015 124.49220325936662 C 713.5405677806581 127.6638848728308 719.911079340912 129.31154177851383 732.65210246142 132.69222810415428 C 745.394568016336 136.07329716344438 751.765800793794 137.79707839803558 764.50826634871 141.39659172169297 C 777.249289469218 144.99569758402762 783.619801029472 146.851941370361 796.36082414998 150.68877606913432 C 809.103289704892 154.52604514294325 815.474522482348 156.51137486552912 828.21698803726 160.58185115314856 C 840.9580111577679 164.65186666690812 847.328522718022 166.73110430513333 860.06954583853 171.04000557258183 C 872.8120113934459 175.34939465858224 879.1832441709039 177.58083033564742 891.92570972582 182.1275770367709 C 904.6681752807359 186.67432373789433 923.78187361311 193.77373907819916 923.78187361311 193.77373907819916 L 933.78187361311 193.77373907819916"
                                  stroke-linejoin="round" stroke="rgba(192,192,192,0.0001)"
                                  stroke-width="22" visibility="visible" data-z-index="2"
                                  class="highcharts-tracker-line"></path>
                        </g>
                        <g data-z-index="0.1"
                           class="highcharts-markers highcharts-series-1 highcharts-spline-series  highcharts-tracker"
                           transform="translate(70,10) scale(1 1)"></g>
                        <g data-z-index="0.1"
                           class="highcharts-series highcharts-series-2 highcharts-spline-series "
                           transform="translate(70,10) scale(1 1)"
                           clip-path="url(#highcharts-6mh5h5f-1985)">
                            <path fill="none"
                                  d="M 0 212.2646669470343 C 0 212.2646669470343 15.6345465417396 212.17543358772798 26.057577569566 212.17543358772798 C 36.48060859739199 212.17543358772798 41.692124111305 212.17543358772798 52.115155139131 212.19957737111088 C 62.538186166957395 212.22372115449377 67.7497016808706 212.29534509906364 78.172732708697 212.4192609371524 C 88.5957637365222 212.5431767752411 93.8072792504348 212.62383080963198 104.23031027826 212.81915656155462 C 114.65334130608801 213.0144823134773 119.864856820002 213.1172476467008 130.28788784783 213.39588969676566 C 140.710918875654 213.6745317468304 145.922434389566 213.84059356871816 156.34546541739 214.21236681187872 C 166.76849644521798 214.58414005503946 171.98001195913199 214.7770149570616 182.40304298696 215.25475591256892 C 192.827516449192 215.732562982241 198.03975318030803 216.01321512873696 208.46422664254 216.6012368748273 C 218.88725767036803 217.18917725634802 224.09877318428198 217.50445548826943 234.52180421211 218.1946612315966 C 244.94483523993398 218.88486697492348 250.15635075384597 219.23903262626877 260.57938178167 220.05226559146237 C 271.002412809498 220.8654985566563 276.213928323412 221.31165165498945 286.63695935124 222.26082605756545 C 297.05999037906804 223.21000046014146 302.27150589298196 223.7169261814997 312.69453692081 224.79813760434234 C 323.117567948634 225.8793490271846 328.329083462546 226.45029362447914 338.75211449037 227.66688317177778 C 349.175145518198 228.88347271907688 354.386661032112 229.5221016163931 364.80969205994 230.8810853408368 C 375.232723087764 232.24006906527998 380.444238601676 232.95134349606164 390.8672696295 234.46180179399502 C 401.290300657328 235.97226009192897 406.501816171242 236.7648974015686 416.92484719907 238.43337683050515 C 427.34787822689395 240.10185625944106 432.559393740806 240.97625163830514 442.98242476863 242.80419893867617 C 453.40545579645806 244.63214623904793 458.616971310372 245.57812181317036 469.0400023382 247.57311333236208 C 479.46303336602807 249.5681048515538 484.674548879942 250.61665934326103 495.09757990777 252.77915653463486 C 505.52061093559405 254.94165372600787 510.732126449506 256.0582334918197 521.15515747733 258.38559928922916 C 531.578188505158 260.71296508663954 536.789704019072 261.9043947729788 547.2127350469 264.41598552168443 C 557.6372085091319 266.9279238472988 562.8494452402481 268.24632650361934 573.27391870248 270.9444219750293 C 583.696949730308 273.64214411096594 588.9084652442219 275.04234702616526 599.33149627205 277.90552954005096 C 609.7545272998739 280.76871205393553 614.9660428137861 282.208708019911 625.38907384161 285.2603345444551 C 635.812104869438 288.31196106900035 641.023620383352 289.9087630914804 651.44665141118 293.1636621627743 C 661.869682439004 296.4185612340669 667.081197952916 298.09247914417506 677.50422898074 301.5348299009213 C 687.927260008568 304.9771806576689 693.1387755224821 306.73284339308333 703.56180655031 310.37541594650895 C 713.9848375781341 314.0179884999332 719.196353092046 315.9053091735226 729.61938411987 319.74769266804606 C 740.042415147698 323.590076162571 755.67696168944 329.58733341912983 755.67696168944 329.58733341912983"
                                  class="highcharts-graph" data-z-index="1" stroke="black"
                                  stroke-width="2" stroke-linejoin="round"
                                  stroke-linecap="round"></path>
                            <path fill="none"
                                  d="M -10 212.2646669470343 L 0 212.2646669470343 C 0 212.2646669470343 15.6345465417396 212.17543358772798 26.057577569566 212.17543358772798 C 36.48060859739199 212.17543358772798 41.692124111305 212.17543358772798 52.115155139131 212.19957737111088 C 62.538186166957395 212.22372115449377 67.7497016808706 212.29534509906364 78.172732708697 212.4192609371524 C 88.5957637365222 212.5431767752411 93.8072792504348 212.62383080963198 104.23031027826 212.81915656155462 C 114.65334130608801 213.0144823134773 119.864856820002 213.1172476467008 130.28788784783 213.39588969676566 C 140.710918875654 213.6745317468304 145.922434389566 213.84059356871816 156.34546541739 214.21236681187872 C 166.76849644521798 214.58414005503946 171.98001195913199 214.7770149570616 182.40304298696 215.25475591256892 C 192.827516449192 215.732562982241 198.03975318030803 216.01321512873696 208.46422664254 216.6012368748273 C 218.88725767036803 217.18917725634802 224.09877318428198 217.50445548826943 234.52180421211 218.1946612315966 C 244.94483523993398 218.88486697492348 250.15635075384597 219.23903262626877 260.57938178167 220.05226559146237 C 271.002412809498 220.8654985566563 276.213928323412 221.31165165498945 286.63695935124 222.26082605756545 C 297.05999037906804 223.21000046014146 302.27150589298196 223.7169261814997 312.69453692081 224.79813760434234 C 323.117567948634 225.8793490271846 328.329083462546 226.45029362447914 338.75211449037 227.66688317177778 C 349.175145518198 228.88347271907688 354.386661032112 229.5221016163931 364.80969205994 230.8810853408368 C 375.232723087764 232.24006906527998 380.444238601676 232.95134349606164 390.8672696295 234.46180179399502 C 401.290300657328 235.97226009192897 406.501816171242 236.7648974015686 416.92484719907 238.43337683050515 C 427.34787822689395 240.10185625944106 432.559393740806 240.97625163830514 442.98242476863 242.80419893867617 C 453.40545579645806 244.63214623904793 458.616971310372 245.57812181317036 469.0400023382 247.57311333236208 C 479.46303336602807 249.5681048515538 484.674548879942 250.61665934326103 495.09757990777 252.77915653463486 C 505.52061093559405 254.94165372600787 510.732126449506 256.0582334918197 521.15515747733 258.38559928922916 C 531.578188505158 260.71296508663954 536.789704019072 261.9043947729788 547.2127350469 264.41598552168443 C 557.6372085091319 266.9279238472988 562.8494452402481 268.24632650361934 573.27391870248 270.9444219750293 C 583.696949730308 273.64214411096594 588.9084652442219 275.04234702616526 599.33149627205 277.90552954005096 C 609.7545272998739 280.76871205393553 614.9660428137861 282.208708019911 625.38907384161 285.2603345444551 C 635.812104869438 288.31196106900035 641.023620383352 289.9087630914804 651.44665141118 293.1636621627743 C 661.869682439004 296.4185612340669 667.081197952916 298.09247914417506 677.50422898074 301.5348299009213 C 687.927260008568 304.9771806576689 693.1387755224821 306.73284339308333 703.56180655031 310.37541594650895 C 713.9848375781341 314.0179884999332 719.196353092046 315.9053091735226 729.61938411987 319.74769266804606 C 740.042415147698 323.590076162571 755.67696168944 329.58733341912983 755.67696168944 329.58733341912983 L 765.67696168944 329.58733341912983"
                                  stroke-linejoin="round" stroke="rgba(192,192,192,0.0001)"
                                  stroke-width="22" visibility="visible" data-z-index="2"
                                  class="highcharts-tracker-line"></path>
                        </g>
                        <g data-z-index="0.1"
                           class="highcharts-markers highcharts-series-2 highcharts-spline-series  highcharts-tracker"
                           transform="translate(70,10) scale(1 1)"></g>
                        <g data-z-index="0.1"
                           class="highcharts-series highcharts-series-3 highcharts-scatter-series  highcharts-tracker"
                           transform="translate(70,10) scale(1 1)"
                           clip-path="url(#highcharts-6mh5h5f-1985)"></g>
                        <g data-z-index="0.1"
                           class="highcharts-markers highcharts-series-3 highcharts-scatter-series  highcharts-tracker"
                           transform="translate(70,10) scale(1 1)">
                            <image preserveAspectRatio="none"
                                   xlink:href="https://wiseselector.flopo.com.br/images/point.png"
                                   x="540" y="91.25" width="20" transform="translate(-10,-10)"
                                   height="20" fill="black" class="highcharts-point"></image>
                        </g>
                        <g data-z-index="0.1"
                           class="highcharts-series highcharts-series-4 highcharts-spline-series "
                           transform="translate(70,10) scale(1 1)"
                           clip-path="url(#highcharts-6mh5h5f-1985)">
                            <path fill="none"
                                  d="M 0 365 C 0 365 19.1136983323728 340.1946427323053 31.856163887288 326.5866833534227 C 44.5971870077956 312.9802643819865 50.9676985680494 309.45192430132624 63.708721688557 296.964054124203 C 76.45118724347219 284.4747701725775 82.8224200209298 275.91322063859866 95.564885575845 264.14379803155083 C 108.305908696351 252.37570771141964 114.676420256604 248.36453561598378 127.41744337711 238.12027180625546 C 140.159908932026 227.8748482247816 146.53114170948402 222.35051985497907 159.2736072644 212.91957955354542 C 172.014630384908 203.48970682515966 178.38514194516202 199.3251613424624 191.12616506567 190.9682392317069 C 203.868630620586 182.61037101859495 210.239863398044 178.6731672323085 222.98232895296 171.1326037438768 C 235.723352073468 163.59289383972083 242.093863633722 160.02535925542986 254.83488675423 153.2675557502377 C 267.577352309146 146.50898718181583 273.948585086604 143.36026241206778 286.69105064152 137.3416735598417 C 299.432073762028 131.32376600587858 305.80258532228197 128.5258357669175 318.54360844279 123.17631473476473 C 331.286073997702 117.8261880736049 337.657306775158 115.34981653039299 350.39977233007 110.59255432656016 C 363.140795450578 105.83583064006858 369.511307010832 103.54654957737199 382.25233013134 99.39135000895374 C 394.994795686256 95.23568002283251 401.366028463714 93.40254792698381 414.10849401863 89.81538044021147 C 426.850959573546 86.22821295343913 433.222192351004 84.57196300942039 445.96465790592 81.45551257509203 C 458.705681026428 78.33941491984852 465.076192586682 76.93199291811844 477.81721570719 74.23401021628183 C 490.559681262106 71.53572207091493 496.93091403956396 70.31477791200427 509.67337959448 67.96483545708327 C 522.414402714988 65.61515901330738 528.784914275242 64.44401819752946 541.52593739575 62.484962969539595 C 554.268402950662 60.525685953343746 560.639635728118 59.726020050731215 573.38210128303 58.169004846618975 C 586.123124403538 56.61216589507641 592.493635963792 55.92201187033313 605.2346590843 54.700327580402586 C 617.977124639216 53.478504981370904 624.3483574166739 52.96769777690279 637.09082297159 52.060237624213414 C 649.831846092098 51.152880195109404 656.2023576523519 50.76029439513268 668.94338077286 50.16328362591912 C 681.6858463277761 49.5662052680302 688.0570791052339 49.42776227750982 700.79954466015 49.075014806457204 C 713.5405677806581 48.72230726606694 719.911079340912 48.43354580659462 732.65210246142 48.399646097311916 C 745.394568016336 48.36574638802921 751.765800793794 48.36574638802921 764.50826634871 48.36574638802921 C 777.249289469218 48.36574638802921 783.619801029472 48.78898020988594 796.36082414998 49.279959794090075 C 809.103289704892 49.77099496298605 815.474522482348 50.05440657597616 828.21698803726 50.820783270779486 C 840.9580111577679 51.5870732125046 847.328522718022 52.07281846449755 860.06954583853 53.11162638541117 C 872.8120113934459 54.15055191165948 879.1832441709039 54.69006337035734 891.92570972582 56.015116888684304 C 904.6681752807359 57.34017040701126 923.78187361311 59.73689397704595 923.78187361311 59.73689397704595"
                                  class="highcharts-graph" data-z-index="1" stroke="#5ef983"
                                  stroke-width="2" stroke-linejoin="round"
                                  stroke-linecap="round"></path>
                            <path fill="none"
                                  d="M -10 365 L 0 365 C 0 365 19.1136983323728 340.1946427323053 31.856163887288 326.5866833534227 C 44.5971870077956 312.9802643819865 50.9676985680494 309.45192430132624 63.708721688557 296.964054124203 C 76.45118724347219 284.4747701725775 82.8224200209298 275.91322063859866 95.564885575845 264.14379803155083 C 108.305908696351 252.37570771141964 114.676420256604 248.36453561598378 127.41744337711 238.12027180625546 C 140.159908932026 227.8748482247816 146.53114170948402 222.35051985497907 159.2736072644 212.91957955354542 C 172.014630384908 203.48970682515966 178.38514194516202 199.3251613424624 191.12616506567 190.9682392317069 C 203.868630620586 182.61037101859495 210.239863398044 178.6731672323085 222.98232895296 171.1326037438768 C 235.723352073468 163.59289383972083 242.093863633722 160.02535925542986 254.83488675423 153.2675557502377 C 267.577352309146 146.50898718181583 273.948585086604 143.36026241206778 286.69105064152 137.3416735598417 C 299.432073762028 131.32376600587858 305.80258532228197 128.5258357669175 318.54360844279 123.17631473476473 C 331.286073997702 117.8261880736049 337.657306775158 115.34981653039299 350.39977233007 110.59255432656016 C 363.140795450578 105.83583064006858 369.511307010832 103.54654957737199 382.25233013134 99.39135000895374 C 394.994795686256 95.23568002283251 401.366028463714 93.40254792698381 414.10849401863 89.81538044021147 C 426.850959573546 86.22821295343913 433.222192351004 84.57196300942039 445.96465790592 81.45551257509203 C 458.705681026428 78.33941491984852 465.076192586682 76.93199291811844 477.81721570719 74.23401021628183 C 490.559681262106 71.53572207091493 496.93091403956396 70.31477791200427 509.67337959448 67.96483545708327 C 522.414402714988 65.61515901330738 528.784914275242 64.44401819752946 541.52593739575 62.484962969539595 C 554.268402950662 60.525685953343746 560.639635728118 59.726020050731215 573.38210128303 58.169004846618975 C 586.123124403538 56.61216589507641 592.493635963792 55.92201187033313 605.2346590843 54.700327580402586 C 617.977124639216 53.478504981370904 624.3483574166739 52.96769777690279 637.09082297159 52.060237624213414 C 649.831846092098 51.152880195109404 656.2023576523519 50.76029439513268 668.94338077286 50.16328362591912 C 681.6858463277761 49.5662052680302 688.0570791052339 49.42776227750982 700.79954466015 49.075014806457204 C 713.5405677806581 48.72230726606694 719.911079340912 48.43354580659462 732.65210246142 48.399646097311916 C 745.394568016336 48.36574638802921 751.765800793794 48.36574638802921 764.50826634871 48.36574638802921 C 777.249289469218 48.36574638802921 783.619801029472 48.78898020988594 796.36082414998 49.279959794090075 C 809.103289704892 49.77099496298605 815.474522482348 50.05440657597616 828.21698803726 50.820783270779486 C 840.9580111577679 51.5870732125046 847.328522718022 52.07281846449755 860.06954583853 53.11162638541117 C 872.8120113934459 54.15055191165948 879.1832441709039 54.69006337035734 891.92570972582 56.015116888684304 C 904.6681752807359 57.34017040701126 923.78187361311 59.73689397704595 923.78187361311 59.73689397704595 L 933.78187361311 59.73689397704595"
                                  stroke-linejoin="round" stroke="rgba(192,192,192,0.0001)"
                                  stroke-width="22" visibility="visible" data-z-index="2"
                                  class="highcharts-tracker-line"></path>
                        </g>
                        <g data-z-index="0.1"
                           class="highcharts-markers highcharts-series-4 highcharts-spline-series  highcharts-tracker"
                           transform="translate(70,10) scale(1 1)"></g>
                    </g>
                    <text x="558" text-anchor="middle" class="highcharts-title" data-z-index="4"
                          style="color:#333333;font-size:18px;fill:#333333;" y="24"></text>
                    <text x="558" text-anchor="middle" class="highcharts-subtitle"
                          data-z-index="4" style="color:#666666;fill:#666666;" y="24"></text>
                    <g data-z-index="6"
                       class="highcharts-data-labels highcharts-series-0 highcharts-spline-series "
                       transform="translate(70,10) scale(1 1)" opacity="1" visibility="visible">
                        <g class="highcharts-label highcharts-data-label highcharts-data-label-color-undefined "
                           data-z-index="1" transform="translate(44,7)">
                            <text x="5" data-z-index="1"
                                  style="font-size:11px;font-weight:bold;color:#000000;fill:#000000;"
                                  y="16">
                                <tspan x="5" y="16" class="highcharts-text-outline"
                                       fill="#FFFFFF" stroke="#FFFFFF" stroke-width="2px"
                                       stroke-linejoin="round" style="">18.03
                                </tspan>
                                <tspan x="5" y="16">18.03</tspan>
                            </text>
                        </g>
                    </g>
                    <g data-z-index="6"
                       class="highcharts-data-labels highcharts-series-1 highcharts-spline-series "
                       transform="translate(70,10) scale(1 1)" opacity="1" visibility="visible">
                        <g class="highcharts-label highcharts-data-label highcharts-data-label-color-undefined "
                           data-z-index="1" transform="translate(41,63)">
                            <text x="5" data-z-index="1"
                                  style="font-size:11px;font-weight:bold;color:#000000;fill:#000000;"
                                  y="16">
                                <tspan x="5" y="16" class="highcharts-text-outline"
                                       fill="#FFFFFF" stroke="#FFFFFF" stroke-width="2px"
                                       stroke-linejoin="round">17.39
                                </tspan>
                                <tspan x="5" y="16">17.39</tspan>
                            </text>
                        </g>
                    </g>
                    <g data-z-index="6"
                       class="highcharts-data-labels highcharts-series-2 highcharts-spline-series "
                       transform="translate(70,10) scale(1 1)" opacity="1" visibility="visible">
                        <g class="highcharts-label highcharts-data-label highcharts-data-label-color-undefined "
                           data-z-index="1" transform="translate(30,219)">
                            <text x="5" data-z-index="1"
                                  style="font-size:11px;font-weight:bold;color:#000000;fill:#000000;"
                                  y="16">
                                <tspan x="5" y="16" class="highcharts-text-outline"
                                       fill="#FFFFFF" stroke="#FFFFFF" stroke-width="2px"
                                       stroke-linejoin="round">14.49
                                </tspan>
                                <tspan x="5" y="16">14.49</tspan>
                            </text>
                        </g>
                    </g>
                    <g class="highcharts-axis-labels highcharts-xaxis-labels "
                       data-z-index="7"></g>
                    <g class="highcharts-axis-labels highcharts-yaxis-labels " data-z-index="7">
                        <text x="55"
                              style="color:#666666;cursor:default;font-size:11px;fill:#666666;"
                              text-anchor="end" transform="translate(0,0)" y="380" opacity="1">
                            120
                        </text>
                        <text x="55"
                              style="color:#666666;cursor:default;font-size:11px;fill:#666666;"
                              text-anchor="end" transform="translate(0,0)" y="334" opacity="1">
                            150
                        </text>
                        <text x="55"
                              style="color:#666666;cursor:default;font-size:11px;fill:#666666;"
                              text-anchor="end" transform="translate(0,0)" y="288" opacity="1">
                            180
                        </text>
                        <text x="55"
                              style="color:#666666;cursor:default;font-size:11px;fill:#666666;"
                              text-anchor="end" transform="translate(0,0)" y="243" opacity="1">
                            210
                        </text>
                        <text x="55"
                              style="color:#666666;cursor:default;font-size:11px;fill:#666666;"
                              text-anchor="end" transform="translate(0,0)" y="197" opacity="1">
                            240
                        </text>
                        <text x="55"
                              style="color:#666666;cursor:default;font-size:11px;fill:#666666;"
                              text-anchor="end" transform="translate(0,0)" y="151" opacity="1">
                            270
                        </text>
                        <text x="55"
                              style="color:#666666;cursor:default;font-size:11px;fill:#666666;"
                              text-anchor="end" transform="translate(0,0)" y="106" opacity="1">
                            300
                        </text>
                        <text x="55"
                              style="color:#666666;cursor:default;font-size:11px;fill:#666666;"
                              text-anchor="end" transform="translate(0,0)" y="60" opacity="1">
                            330
                        </text>
                        <text x="55"
                              style="color:#666666;cursor:default;font-size:11px;fill:#666666;"
                              text-anchor="end" transform="translate(0,0)" y="15" opacity="1">
                            360
                        </text>
                    </g>
                    <g class="highcharts-axis-labels highcharts-yaxis-labels "
                       data-z-index="7"></g>
                    <g class="highcharts-axis-labels highcharts-yaxis-labels " data-z-index="7">
                        <text x="1080"
                              style="color:#666666;cursor:default;font-size:11px;fill:#666666;"
                              text-anchor="start" transform="translate(0,0)" y="380"
                              opacity="1">0
                        </text>
                        <text x="1080"
                              style="color:#666666;cursor:default;font-size:11px;fill:#666666;"
                              text-anchor="start" transform="translate(0,0)" y="136"
                              opacity="1">0.6
                        </text>
                        <text x="1080"
                              style="color:#666666;cursor:default;font-size:11px;fill:#666666;"
                              text-anchor="start" transform="translate(0,0)" y="319"
                              opacity="1">0.15
                        </text>
                        <text x="1080"
                              style="color:#666666;cursor:default;font-size:11px;fill:#666666;"
                              text-anchor="start" transform="translate(0,0)" y="258"
                              opacity="1">0.3
                        </text>
                        <text x="1080"
                              style="color:#666666;cursor:default;font-size:11px;fill:#666666;"
                              text-anchor="start" transform="translate(0,0)" y="197"
                              opacity="1">0.45
                        </text>
                        <text x="1080"
                              style="color:#666666;cursor:default;font-size:11px;fill:#666666;"
                              text-anchor="start" transform="translate(0,0)" y="75" opacity="1">
                            0.75
                        </text>
                        <text x="1080"
                              style="color:#666666;cursor:default;font-size:11px;fill:#666666;"
                              text-anchor="start" transform="translate(0,0)" y="15" opacity="1">
                            0.9
                        </text>
                    </g>
                    <g class="highcharts-axis-labels highcharts-yaxis-labels "
                       data-z-index="7"></g>
                    <g class="highcharts-axis-labels highcharts-yaxis-labels "
                       data-z-index="7"></g>
                </svg>
            </div>
            <div class="svg-wrap">
                <svg version="1.1" class="highcharts-root"
                     style="font-family:&quot;Lucida Grande&quot;, &quot;Lucida Sans Unicode&quot;, Arial, Helvetica, sans-serif;font-size:12px;"
                     xmlns="http://www.w3.org/2000/svg" width="1010" height="150"
                     viewBox="0 0 1010 150">
                    <desc>Created with Highcharts 6.2.0</desc>
                    <defs>
                        <clipPath id="highcharts-6mh5h5f-2112">
                            <rect x="0" y="0" width="930" height="85" fill="none"></rect>
                        </clipPath>
                    </defs>
                    <rect fill="#ffffff" class="highcharts-background" x="0" y="0" width="1010"
                          height="150" rx="0" ry="0"></rect>
                    <rect fill="none" class="highcharts-plot-background" x="70" y="10"
                          width="930" height="85"></rect>
                    <g class="highcharts-grid highcharts-xaxis-grid " data-z-index="1">
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 69.5 10 L 69.5 95"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 159.5 10 L 159.5 95"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 249.5 10 L 249.5 95"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 339.5 10 L 339.5 95"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 428.5 10 L 428.5 95"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 518.5 10 L 518.5 95"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 608.5 10 L 608.5 95"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 698.5 10 L 698.5 95"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 788.5 10 L 788.5 95"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 878.5 10 L 878.5 95"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 968.5 10 L 968.5 95"
                              opacity="1"></path>
                    </g>
                    <g class="highcharts-grid highcharts-yaxis-grid " data-z-index="1">
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 70 95.5 L 1000 95.5"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 70 53.5 L 1000 53.5"
                              opacity="1"></path>
                        <path fill="none" stroke="#e5e0e0" stroke-width="1" data-z-index="1"
                              class="highcharts-grid-line" d="M 70 9.5 L 1000 9.5"
                              opacity="1"></path>
                    </g>
                    <g class="highcharts-grid highcharts-yaxis-grid " data-z-index="1"></g>
                    <rect fill="none" class="highcharts-plot-border" data-z-index="1" x="70"
                          y="10" width="930" height="85"></rect>
                    <g class="highcharts-axis highcharts-xaxis " data-z-index="2">
                        <path fill="none" class="highcharts-tick" stroke="#ccd6eb"
                              stroke-width="1" d="M 69.5 95 L 69.5 105" opacity="1"></path>
                        <path fill="none" class="highcharts-tick" stroke="#ccd6eb"
                              stroke-width="1" d="M 159.5 95 L 159.5 105" opacity="1"></path>
                        <path fill="none" class="highcharts-tick" stroke="#ccd6eb"
                              stroke-width="1" d="M 249.5 95 L 249.5 105" opacity="1"></path>
                        <path fill="none" class="highcharts-tick" stroke="#ccd6eb"
                              stroke-width="1" d="M 339.5 95 L 339.5 105" opacity="1"></path>
                        <path fill="none" class="highcharts-tick" stroke="#ccd6eb"
                              stroke-width="1" d="M 428.5 95 L 428.5 105" opacity="1"></path>
                        <path fill="none" class="highcharts-tick" stroke="#ccd6eb"
                              stroke-width="1" d="M 518.5 95 L 518.5 105" opacity="1"></path>
                        <path fill="none" class="highcharts-tick" stroke="#ccd6eb"
                              stroke-width="1" d="M 608.5 95 L 608.5 105" opacity="1"></path>
                        <path fill="none" class="highcharts-tick" stroke="#ccd6eb"
                              stroke-width="1" d="M 698.5 95 L 698.5 105" opacity="1"></path>
                        <path fill="none" class="highcharts-tick" stroke="#ccd6eb"
                              stroke-width="1" d="M 788.5 95 L 788.5 105" opacity="1"></path>
                        <path fill="none" class="highcharts-tick" stroke="#ccd6eb"
                              stroke-width="1" d="M 878.5 95 L 878.5 105" opacity="1"></path>
                        <path fill="none" class="highcharts-tick" stroke="#ccd6eb"
                              stroke-width="1" d="M 968.5 95 L 968.5 105" opacity="1"></path>
                        <text x="535" data-z-index="7" text-anchor="middle"
                              transform="translate(0,0)" class="highcharts-axis-title"
                              style="color:#666666;fill:#666666;" y="133">
                            <tspan>Flow - gal/min</tspan>
                        </text>
                        <path fill="none" class="highcharts-axis-line" stroke="#ccd6eb"
                              stroke-width="1" data-z-index="7"
                              d="M 70 95.5 L 1000 95.5"></path>
                    </g>
                    <g class="highcharts-axis highcharts-yaxis " data-z-index="2">
                        <text x="29.015625" data-z-index="7" text-anchor="middle"
                              transform="translate(0,0) rotate(270 29.015625 52.5)"
                              class="highcharts-axis-title" style="color:#666666;fill:#666666;"
                              y="52.5">
                            <tspan>NPSH - ft</tspan>
                        </text>
                        <path fill="none" class="highcharts-axis-line" stroke="#ccd6eb"
                              stroke-width="1" data-z-index="7" d="M 69.5 10 L 69.5 95"></path>
                    </g>
                    <g class="highcharts-axis highcharts-yaxis " data-z-index="2">
                        <path fill="none" class="highcharts-axis-line" stroke="#ccd6eb"
                              stroke-width="1" data-z-index="7"
                              d="M 1000.5 10 L 1000.5 95"></path>
                    </g>
                    <g class="highcharts-series-group" data-z-index="3">
                        <g data-z-index="0.1"
                           class="highcharts-series highcharts-series-0 highcharts-spline-series highcharts-color-0 "
                           transform="translate(70,10) scale(1 1)"
                           clip-path="url(#highcharts-6mh5h5f-2112)">
                            <path fill="none"
                                  d="M 0 59.36534243947881 C 0 59.36534243947881 19.051837377997202 63.651769638204016 31.753062296662 64.42006256402188 C 44.4528494493184 65.18835548983974 50.8027430256466 64.91773111218284 63.502530178303 65.18835548983974 C 76.2037550969678 65.45901050537478 82.5543675563002 65.56647306277404 95.255592474965 65.77326104700174 C 107.955379627623 65.98002562303564 114.305273203952 66.06485963629594 127.00506035661 66.22223689049373 C 139.706285275274 66.37963196165676 146.056897734606 66.45307538132553 158.75812265327 66.56019186040379 C 171.45790980592602 66.66729621400333 177.807803382254 66.70809831138023 190.50759053491 66.75778897218824 C 203.208815453574 66.80748525856636 209.559427912906 66.80865922836914 222.26065283157 66.80865922836914 C 234.960439984226 66.80865922836914 241.310333560554 66.80865922836914 254.01012071321 66.78745098925111 C 266.711345631874 66.76624275013309 273.061958091206 66.72668607309434 285.76318300987 66.64477411186327 C 298.462970162526 66.56287142298461 304.812863738854 66.49918604292782 317.51265089151 66.3779143639768 C 330.21387581017797 66.25662895563835 336.564488269512 66.19689746229933 349.26571318818 66.03838139363958 C 361.965500340836 65.87988326884094 368.315393917164 65.79643865371455 381.01518106982 65.5853788803308 C 393.716405988484 65.37429521248613 400.067018447816 65.23983163767673 412.76824336648 64.98302279056853 C 425.469468285144 64.72621394346032 431.82008074447606 64.60450096203311 444.52130566314 64.30133464478982 C 457.22109281579594 63.998202645671626 463.570986392124 63.83493291660159 476.27077354478 63.46727699966478 C 488.97199846344404 63.09957945973275 495.32261092277605 62.88541025034453 508.02383584144 62.46295100261773 C 520.723622994096 62.04053957685693 527.073516570424 61.83143085467178 539.77330372308 61.355100315945805 C 552.474528641748 60.87871585097282 558.825141101082 60.6364415383442 571.52636601975 60.081163493370305 C 584.2261531724059 59.52594830531812 590.576046748734 59.21646579488311 603.27583390139 58.5788672333806 C 615.977058820054 57.941196488184964 622.3276712793861 57.616517225653084 635.02889619805 56.89299022662494 C 647.728683350706 56.16954513013231 654.078576927034 55.7818961971747 666.77836407969 54.961436994578676 C 679.4795889983541 54.14088490630368 685.830201457686 53.71137977938518 698.53142637635 52.79046199944739 C 711.231213529006 51.869648466484875 717.581107105334 51.39694237627 730.28089425799 50.35710871232789 C 742.9821191766539 49.31715732692495 749.332731635986 48.75282111107114 762.03395655465 47.590999376084795 C 774.733743707306 46.429309158161466 781.0836372836341 45.848785249015286 793.78342443629 44.5483288300537 C 806.4846493549579 43.24772518405463 812.835261814292 42.54484496760156 825.53648673296 41.088349213683166 C 838.236273885616 39.63201833363364 844.586167461944 38.882324902384156 857.2859546146 37.2662622451339 C 869.987179533264 35.65001663049014 876.3377919925961 34.804623472059006 889.03901691126 33.00757853394814 C 901.740241829924 31.210533595837266 920.79207920792 28.281037554579576 920.79207920792 28.281037554579576"
                                  class="highcharts-graph" data-z-index="1" stroke="#7cb5ec"
                                  stroke-width="2" stroke-linejoin="round"
                                  stroke-linecap="round"></path>
                            <path fill="none"
                                  d="M -10 59.36534243947881 L 0 59.36534243947881 C 0 59.36534243947881 19.051837377997202 63.651769638204016 31.753062296662 64.42006256402188 C 44.4528494493184 65.18835548983974 50.8027430256466 64.91773111218284 63.502530178303 65.18835548983974 C 76.2037550969678 65.45901050537478 82.5543675563002 65.56647306277404 95.255592474965 65.77326104700174 C 107.955379627623 65.98002562303564 114.305273203952 66.06485963629594 127.00506035661 66.22223689049373 C 139.706285275274 66.37963196165676 146.056897734606 66.45307538132553 158.75812265327 66.56019186040379 C 171.45790980592602 66.66729621400333 177.807803382254 66.70809831138023 190.50759053491 66.75778897218824 C 203.208815453574 66.80748525856636 209.559427912906 66.80865922836914 222.26065283157 66.80865922836914 C 234.960439984226 66.80865922836914 241.310333560554 66.80865922836914 254.01012071321 66.78745098925111 C 266.711345631874 66.76624275013309 273.061958091206 66.72668607309434 285.76318300987 66.64477411186327 C 298.462970162526 66.56287142298461 304.812863738854 66.49918604292782 317.51265089151 66.3779143639768 C 330.21387581017797 66.25662895563835 336.564488269512 66.19689746229933 349.26571318818 66.03838139363958 C 361.965500340836 65.87988326884094 368.315393917164 65.79643865371455 381.01518106982 65.5853788803308 C 393.716405988484 65.37429521248613 400.067018447816 65.23983163767673 412.76824336648 64.98302279056853 C 425.469468285144 64.72621394346032 431.82008074447606 64.60450096203311 444.52130566314 64.30133464478982 C 457.22109281579594 63.998202645671626 463.570986392124 63.83493291660159 476.27077354478 63.46727699966478 C 488.97199846344404 63.09957945973275 495.32261092277605 62.88541025034453 508.02383584144 62.46295100261773 C 520.723622994096 62.04053957685693 527.073516570424 61.83143085467178 539.77330372308 61.355100315945805 C 552.474528641748 60.87871585097282 558.825141101082 60.6364415383442 571.52636601975 60.081163493370305 C 584.2261531724059 59.52594830531812 590.576046748734 59.21646579488311 603.27583390139 58.5788672333806 C 615.977058820054 57.941196488184964 622.3276712793861 57.616517225653084 635.02889619805 56.89299022662494 C 647.728683350706 56.16954513013231 654.078576927034 55.7818961971747 666.77836407969 54.961436994578676 C 679.4795889983541 54.14088490630368 685.830201457686 53.71137977938518 698.53142637635 52.79046199944739 C 711.231213529006 51.869648466484875 717.581107105334 51.39694237627 730.28089425799 50.35710871232789 C 742.9821191766539 49.31715732692495 749.332731635986 48.75282111107114 762.03395655465 47.590999376084795 C 774.733743707306 46.429309158161466 781.0836372836341 45.848785249015286 793.78342443629 44.5483288300537 C 806.4846493549579 43.24772518405463 812.835261814292 42.54484496760156 825.53648673296 41.088349213683166 C 838.236273885616 39.63201833363364 844.586167461944 38.882324902384156 857.2859546146 37.2662622451339 C 869.987179533264 35.65001663049014 876.3377919925961 34.804623472059006 889.03901691126 33.00757853394814 C 901.740241829924 31.210533595837266 920.79207920792 28.281037554579576 920.79207920792 28.281037554579576 L 930.79207920792 28.281037554579576"
                                  stroke-linejoin="round" stroke="rgba(192,192,192,0.0001)"
                                  stroke-width="22" visibility="visible" data-z-index="2"
                                  class="highcharts-tracker-line"></path>
                        </g>
                        <g data-z-index="0.1"
                           class="highcharts-markers highcharts-series-0 highcharts-spline-series highcharts-color-0 highcharts-tracker"
                           transform="translate(70,10) scale(1 1)"></g>
                    </g>
                    <text x="505" text-anchor="middle" class="highcharts-title" data-z-index="4"
                          style="color:#333333;font-size:18px;fill:#333333;" y="24"></text>
                    <text x="505" text-anchor="middle" class="highcharts-subtitle"
                          data-z-index="4" style="color:#666666;fill:#666666;" y="24"></text>
                    <g class="highcharts-axis-labels highcharts-xaxis-labels " data-z-index="7">
                        <text x="70"
                              style="color:#666666;cursor:default;font-size:11px;fill:#666666;"
                              text-anchor="middle" transform="translate(0,0)" y="114"
                              opacity="1">0
                        </text>
                        <text x="159.86037552825"
                              style="color:#666666;cursor:default;font-size:11px;fill:#666666;"
                              text-anchor="middle" transform="translate(0,0)" y="114"
                              opacity="1">250
                        </text>
                        <text x="249.7207510565"
                              style="color:#666666;cursor:default;font-size:11px;fill:#666666;"
                              text-anchor="middle" transform="translate(0,0)" y="114"
                              opacity="1">500
                        </text>
                        <text x="339.58112658475"
                              style="color:#666666;cursor:default;font-size:11px;fill:#666666;"
                              text-anchor="middle" transform="translate(0,0)" y="114"
                              opacity="1">750
                        </text>
                        <text x="429.44150211299"
                              style="color:#666666;cursor:default;font-size:11px;fill:#666666;"
                              text-anchor="middle" transform="translate(0,0)" y="114"
                              opacity="1">1000
                        </text>
                        <text x="519.30187764124"
                              style="color:#666666;cursor:default;font-size:11px;fill:#666666;"
                              text-anchor="middle" transform="translate(0,0)" y="114"
                              opacity="1">1250
                        </text>
                        <text x="609.16225316949"
                              style="color:#666666;cursor:default;font-size:11px;fill:#666666;"
                              text-anchor="middle" transform="translate(0,0)" y="114"
                              opacity="1">1500
                        </text>
                        <text x="699.02262869774"
                              style="color:#666666;cursor:default;font-size:11px;fill:#666666;"
                              text-anchor="middle" transform="translate(0,0)" y="114"
                              opacity="1">1750
                        </text>
                        <text x="788.88300422599"
                              style="color:#666666;cursor:default;font-size:11px;fill:#666666;"
                              text-anchor="middle" transform="translate(0,0)" y="114"
                              opacity="1">2000
                        </text>
                        <text x="878.74337975424"
                              style="color:#666666;cursor:default;font-size:11px;fill:#666666;"
                              text-anchor="middle" transform="translate(0,0)" y="114"
                              opacity="1">2250
                        </text>
                        <text x="968.60375528249"
                              style="color:#666666;cursor:default;font-size:11px;fill:#666666;"
                              text-anchor="middle" transform="translate(0,0)" y="114"
                              opacity="1">2500
                        </text>
                    </g>
                    <g class="highcharts-axis-labels highcharts-yaxis-labels " data-z-index="7">
                        <text x="55"
                              style="color:#666666;cursor:default;font-size:11px;fill:#666666;"
                              text-anchor="end" transform="translate(0,0)" y="100" opacity="1">0
                        </text>
                        <text x="55"
                              style="color:#666666;cursor:default;font-size:11px;fill:#666666;"
                              text-anchor="end" transform="translate(0,0)" y="57" opacity="1">25
                        </text>
                        <text x="55"
                              style="color:#666666;cursor:default;font-size:11px;fill:#666666;"
                              text-anchor="end" transform="translate(0,0)" y="15" opacity="1">50
                        </text>
                    </g>
                    <g class="highcharts-axis-labels highcharts-yaxis-labels "
                       data-z-index="7"></g>
                </svg>
            </div>
        </div>


        <div class="orders page">
            <h3 class="h6 text-al">All Oders</h3>
            <hr>
            <table class="table">
                <thead>
                <tr>
                    <th>Order ID:</th>
                    <th>Order Type</th>
                    <th>Link</th>
                </tr>
                </thead>
                <tbody>
                <tr>
                    <td>0</td>
                    <td>Comercial</td>
                    <td><a href="">Click</a> </td>
                </tr>
                </tbody>
            </table>
        </div>
    </section>
</template>

<script>
    import jsPDF from 'jspdf';
    import 'jspdf-autotable';

    export default {

        methods: {
            makePdf() {
                let doc = new jsPDF();

                //page-1
                doc.setFont('DejaVu Sans');
                doc.setFontType('normal');
                doc.text(20, 20, 'Data/Cliente/Projeto/Cotação');
                doc.setFontSize(14);
                doc.text(20, 26, 'Rio de Janeiro, 2020/02/05');
                doc.text(20, 48, 'Cliente: Craveiro\'s Ltda');
                doc.text(20, 54, 'Endereço: undefined');
                doc.text(120, 48, 'Projeto: Bomba OH2 para petróleo');
                doc.setFontType('bold');
                doc.text(80, 70, 'Cotação Nº *quote-number');
                doc.setFontType('normal');
                doc.text(20, 100, 'POLÍTICA DE QUALIDADE RP:');
                doc.text(20, 108, 'A Flopo do Brasil Ltda compromete-se em estabelecer e melhorar continuamente a \n' +
                    'qualidade dos seus produtos e serviços visando atender plenamente seus clientes,\n' +
                    'acionistas e colaboradores. A gestão de qualidade da empresa baseia-se em fornecimento\n' +
                    'de produtos de alta tecnologia, capacitação profissional, respeito mútuo e crescimento\n' +
                    'contínuo.');
                doc.text(20, 160, 'ESCOPO DE FORNECIMENTO:');
                doc.text(20, 168, 'A Ruhrpumpen é uma empresa multinacional, com plantas de fabricação em vários países,\n' +
                    ' e como tal, poderemos utilizar abastecimento global para apoiar o processo de fabricação.\n' +
                    'Nosso preço baseia-se estritamente no escopo de fornecimento descrito nesta proposta.\n' +
                    'Equipamentos ou acessórios adicionais, não mencionados no escopo de fornecimento,\n' +
                    'serão orçados separadamente. Entre em contato com a Ruhrpumpen para consulta de itens\n' +
                    'adicionais, prazos de entrega e preços. ');
                //page-2
                doc.addPage();
                doc.text(20, 20, 'ESPECIFICAÇÕES:');
                doc.text(20, 48, 'VALIDADE:');
                doc.text(20, 54, '*Esta proposta é valida por 30 dias a partir da data da emissão. Para pedidos com "espera \n' +
                    ' para aprovação" da documentação, os preços cotados permanecerão firmes até a data de \n' +
                    ' embarque, se a liberação para fabricação pelo cliente não ultrapassar 30 dias da data de \n' +
                    ' envio para aprovação. Caso contrario, poderá ser aplicado um acréscimo nos preços e a \n' +
                    ' postergação do prazo de entrega.');
                doc.text(20, 98, 'IMPOSTOS:');
                doc.text(20, 106, 'A Ruhrpumpen é uma empresa multinacional, com plantas de fabricação em vários países, e\n' +
                    ' como tal, poderemos utilizar abastecimento global para apoiar o processo de fabricação.\n' +
                    ' Nosso preço baseia-se estritamente no escopo de fornecimento descrito nesta proposta. \n' +
                    'Equipamentos ou acessórios adicionais, não mencionados no escopo de fornecimento, serão \n' +
                    'orçados separadamente. Entre em contato com a Ruhrpumpen para consulta de itens \n' +
                    'adicionais, prazos de entrega e preços.');
                doc.text(20, 155, 'Assinatura');
                //page-3
                doc.addPage();
                doc.setFontStyle('bold');
                doc.setFontSize(50);
                doc.text(85, 140, 'Price');
                doc.text(85, 155, 'Sheet');
                //page-4
                doc.addPage('a4', 'landscape');
                doc.autoTable({
                    html: '#myTable', styles: {fillColor: null},
                    headStyles: {textColor: [0, 0, 0]},
                    alternateRowStyles: {fillColor: null},
                    // fontSize: 15
                });
                //page-5
                doc.addPage('a4', 'partial');
                doc.setFontStyle('bold');
                doc.setFontSize(50);
                doc.text(85, 140,'Scope of\n' +
                    'Supply');
                //page-6
                doc.addPage();
                doc.setFontSize(14);
                doc.setFillColor(0, 0, 0);
                doc.rect(10, 10, 190, 8, 'F');

                doc.setTextColor(255, 255, 255);
                doc.text(85, 15, 'Scope of Supply');
                doc.autoTable({html: '#table2', margin: {top: 20}});

                doc.setFillColor(0, 0, 0);
                doc.rect(10, 42, 190, 8, 'F');
                doc.text(80, 48, '007 - SCE | Size: SCE 10x8x18');


                doc.autoTable({
                    html: '#table3', margin: {top: 10}
                });

                //page-7
                doc.addPage();
                doc.setFontSize(14);
                doc.setFillColor(0, 0, 0);
                doc.rect(10, 10, 190, 8, 'F');

                doc.setTextColor(255, 255, 255);
                doc.text(85, 15, 'Scope of Supply');
                doc.autoTable({html: '#table4', margin: {top: 20}});

                doc.setFillColor(0, 0, 0);
                doc.rect(10, 42, 190, 8, 'F');
                doc.text(80, 48, '007 - SCE | Size: SCE 10x8x18');

                doc.autoTable({
                    html: '#table5', margin: {top: 10}
                });

                //page-8
                doc.addPage();
                doc.setFontSize(14);
                doc.setFillColor(0, 0, 0);
                doc.rect(10, 10, 190, 8, 'F');

                doc.setTextColor(255, 255, 255);
                doc.text(85, 15, 'Scope of Supply');
                doc.autoTable({html: '#table6', margin: {top: 20}});

                doc.setFillColor(0, 0, 0);
                doc.rect(10, 42, 190, 8, 'F');
                doc.text(80, 48, '010 - VCT - KX | Size: Bomba vertical VCT - Novo teste');

                doc.autoTable({
                    html: '#table7', margin: {top: 10}
                });

                //page-9
                doc.addPage();
                doc.setTextColor(0, 0, 0);
                doc.setFontStyle('bold');
                doc.setFontSize(50);
                doc.text(85, 140, 'Datasheet');

                //page-10
                doc.addPage('a4', 'landscape');
                doc.setFontStyle('bold');
                doc.setFontSize(13);
                doc.text(80, 20, 'Tag: B-2351104A/C');
                doc.setFontStyle('normal');
                doc.text(120, 20, '- Bomba Click Pump | Size: Modelo Click');
                doc.setFontStyle('bold');
                doc.text(10, 30, 'Pump Information');
                doc.text(10, 35, 'Tag:');
                doc.text(10, 40, 'Quantity:');
                doc.text(10, 45, 'Line:');
                doc.text(10, 50, 'Size:');
                doc.text(10, 55, 'Service:');
                doc.text(10, 65, 'Duty Conditions');
                doc.text(10, 75, 'Flow: ');
                doc.text(10, 85, 'Head:');
                doc.text(10, 95, 'Frequency:');
                doc.text(10, 105, 'Speed Criteria:');
                doc.text(10, 115, 'Pump Operation:');
                doc.text(10, 125, 'Performance Details');

                doc.setFontStyle('normal');
                doc.text(150,35,'B-2351104A/C');
                doc.text(150,40,'3');
                doc.text(150,45,'Bomba Click Pump');
                doc.text(150,50,'Modelo Click');
                doc.text(150,55,'Water');

                doc.text(60,75,'200.00 m3/h');
                doc.text(60,85,'755.8 m');
                doc.text(60,95,'60Hz/3585 RPM');
                doc.text(60,105,'All Suitable Asyc\n' +
                    ' Speed');
                doc.text(60,115,'-');

                doc.setFontStyle('bold');
                doc.text(100,75,'NPSHa:');
                doc.text(100,85,'Suction \n' +
                    'Pressure:');
                doc.text(100,95,'vapor Pressure:');
                doc.text(100,105,'Density:');
                doc.text(100,115,'Viscosity:');

                doc.setFontStyle('normal');
                doc.text(135,75,'49.6 m');
                doc.text(135,85,'(0/0/1.01325)\n' +
                    'ft');
                doc.text(135,95,'(//) ft');
                doc.text(135,105,'(0/0/1.04) S.G.');
                doc.text(135,115,'3.46 cP');

                doc.setFontStyle('bold');
                doc.text(165,75,'Liquid:');
                doc.text(165,85,'Temperature:');
                doc.text(165,95,'Sphere Diameter\n' +
                    'Size:');
                doc.text(165,105,'Solids Con by Vol:');
                doc.text(165,115,'Cq/Ch/Ce/Cn:');

                doc.setFontStyle('normal');
                doc.text(205,85,'(60/60/60) C');
                doc.text(205,105,'00');
                doc.text(205,115,'1.00/1.00\n' +
                    '/1.00/1.00');

                doc.setFontStyle('bold');
                doc.text(10,125,'Performance Details');
                doc.text(10,130,'Rated Flow:');
                doc.text(10,145,'Normal Flow:');

                doc.text(65,130,'Differential Head (Hr):');
                doc.text(65,145,'Shutoff Head:');

                doc.text(130,130,'Hydraulic Power:');
                doc.text(130,145,'Rated Efficiency:');

                doc.text(190,130,'NPSHr:');
                doc.text(190,145,'NPSHa\n' +
                    '- NPSHr:');

                doc.text(240,130,'Dmax:');
                doc.text(240,145,'Drated:');

                doc.setFontStyle('normal');

                doc.text(40,130,'200 m3/h\n' +
                    '(78.38%)');
                doc.text(40,145,'-');

                doc.text(111,130,'755.8 m');
                doc.text(111,145,'919.64 m');

                doc.text(165,130,'427.62 kW');
                doc.text(165,145,'73.61%');

                doc.text(210,130,'4.85 m');
                doc.text(210,145,'44.75 m');

                doc.text(260,130,'11.42');
                doc.text(260,145,'10.89');

                //page-11
                doc.addPage('a4', 'partial');
                doc.setFontStyle('bold');
                doc.setFontSize(50);
                doc.text(65, 140, 'Performance\n Curves');

                //page-12
                doc.addPage('a4','landscape');
                var imgData = 'data:image/png;base64,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'
                var imgData2 ='data:image/png;base64,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'
                var imgData3 ='data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAA/EAAACOCAYAAAB5XYgcAAAgAElEQVR4nO3dwa8a6Znv8flrvWDDpjYlTS1uJVItpqQrpDAL1C0Wl0gsBinRyEIt0Q7KvcQScYZEqD3II9wtOh06ou3gpLE75XR+dwGcw+FQHKhDPS9Q34/0Kmo6tvG3KajnVFH1LwIAAAAAABfhX1w/AQAAAAAAcBiGeAAAAAAALgRDPAAAAAAAF4IhHgAAAACAC8EQDwAAAADAhWCIBwAAAADgQjDEAwAAAABwIRjiAQAAAAC4EE6H+EW/olLZk+/78n1fQdjUSJKUaNKpKgpDhWGoSmuoucsnCgAAAADAGXA6xM+7scLW5P6/mLYVhi1NEkmaqRsHqg8T66cHAAAAAMBZcTrET9uhos7s3uOzTqRgY7ifd2P5zfGj/qxvvvqKxWKxWCwWi8VisVgss5UHp0P8uBnIjyqKo1BhGKvRmyqRNGkGirsbJ9APaipXB8p6LP7Fy/s/KMDp5fUixV10tkHn/NHYBp1t0NkGnW3Q2QadbbjunMcs6vZ0+nFfvdFsOZzPB6r7gZoThvhL5XoDKQo626Bz/mhsg8426GyDzjbobIPONlx3vrohftuw7qnSW2jeje+dTh884nR6hngbrjeQoqCzDTrnj8Y26GyDzjbobIPONuhsw3XnKxviEw0bkWr91RH3xUiNYHkkXtO2orCpcSJJU3WiQI1R9gvbMcTbcL2BFAWdbdA5fzS2QWcbdLZBZxt0tkFnG647X9kQL2nWVz0KFIShgiBUtTNZnTKfaNKt3d5irj3S4hF/DEO8DdcbSFHQ2Qad80djG3S2QWcbdLZBZxt0tuG68/UN8UYY4m243kCKgs426Jw/Gtugsw0626CzDTrboLMN150Z4jNiiLfhegMpCjrboHP+aGyDzjbobIPONuhsg842XHdmiM+IId6G6w2kKOhsg875o7ENOtugsw0626CzDTrbcN2ZIT4jhngbrjeQoqCzDTrnj8Y26GyDzjbobIPONuhsw3VnhviMGOJtuN5AioLONuicPxrboLMNOtugsw0626CzDdedGeIzYoi34XoDKQo626Bz/mhsg8426GyDzjbobIPONlx3ZojPiCHehusNpCjobIPO+aOxDTrboLMNOtugsw0623DdmSE+I4Z4G643kKKgsw0654/GNuhsg8426GyDzjbobMN1Z4b4jBjibbjeQIqCzjbonD8a26CzDTrboLMNOtugsw3XnRniM2KIt+F6AykKOtugc/5obIPONuhsg8426GyDzjZcd2aIz4gh3obrDaQo6GyDzvmjsQ0626CzDTrboLMNOttw3ZkhPiOGeBuuN5CioLMNOuePxjbobIPONuhsg8426GzDdWeHQ/xE3dZA8x2Pd+pdTU78pE6NId6G6w2kKOhsg875o7ENOtugsw0626CzDTrbcN3ZyRC/GPfUadcUerGa7bbam6tZkV+ua3jyp3VaDPE2XG8gRUFnG3TOH41t0NkGnW3Q2QadbdDZhuvOTob4ZDZSv1NT4IWqNRpq3FktdYbnPyAzxNtwvYEUBZ1t0Dl/NLZBZxt0tkFnG3S2QWcbrjs7GOKn6rX6miUv9Z8/7+lSR2GGeBuuN5CioLMNOuePxjbobIPONuhsg8426GzDdWcHQ/xQdS9Uo9tQ5FfV7vfVv7fGO74rf14Y4m243kCKgs426Jw/Gtugsw0626CzDTrboLMN150dDPGJpv2matVQXjlQXKmosr2qHY1P/rROiyHehusNpCjobIPO+aOxDTrboLMNOtugsw0623Dd2enV6Xud4dkfcU/DEG/D9QZSFHS2Qef80dgGnW3Q2QadbdDZBp1tuO7MfeIzYoi34XoDKQo626Bz/mhsg8426GyDzjbobIPONlx3ZojPiCHehusNpCjobIPO+aOxDTrboLMNOtugsw0623DdmSE+I4Z4G643kKKgsw0654/GNuhsg8426GyDzjbobMN15zMZ4hPNJlMtTv5U8sMQb8P1BlIUdLZB5/zR2AadbdDZBp1t0NkGnW2cqvOHj//Ul28+6r++/kHPXr3Xp8/f6Xdf//DgrzuTIX6khh+re0FXuWOIt8EbkQ0626Bz/mhsg8426GyDzjbobIPONo7t/Kd3/9DLb/+uZ6/eq/WHv+nT5+/0r0+/27kaL/764O/HEJ8RQ7wN3ohs0NkGnfNHYxt0tkFnG3S2QWcbdLaxq/Pb9z/qyzcf9ZsvP+jpF9/r0+fvFD97mzqsr9cnz+f6j9//TZ+/Wujlt3/Xh4//fPDPP5MhfqpuranhBZ1PzxBvgzciG3S2Qef80dgGnW3Q2QadbdDZBp3ztT79/dnvv9GzV+/18xd/1c/+718eHNR/9uu/6JPnc33+aqHfff2DXn+XHDSspzmTIf7yMMTb4I3IBp1t0Dl/NLZBZxt0tkFnG3S2QefH2/6e+s9f/HXv6e/r9ZPP3uiT53M9/eJ7ff5qodffJfrTu3/k8hwZ4jNiiLfBG5ENOtugc/5obIPONuhsg8426GyDzofJOqivT3//5Nff3pz+/vq7xPz5M8RnxBBvgzciG3S2Qef80dgGnW3Q2QadbdDZBp1vbX5HfX3l92MG9caLv6ae/u66M0N8RgzxNlxvIEVBZxt0zh+NbdDZBp1t0NkGnW0UrfOXbz7eXPV9fTG5Q76jvj71fd+gvo/rzg6G+JmG3Y46nT2rO9S5j8gM8TZcbyBFQWcbdM4fjW3Q2QadbdDZBp1tXFvnP737R+aj6f/27O29K7+f6tR3150dDPFjdaoVVSrrFckvlRXEG49VOxqf/GmdFkO8DdcbSFHQ2Qad80djG3S2QWcbdLZBZxuX1nl7SF9/N/2nn705/Pvpq6u+530xuU2uO5/B6fTji7tHvMQQb8X1BlIUdLZB5/zR2AadbdDZBp1t0NnGuXV+7JC+vjXb+orv66Ppj7k92ym47swQnxFDvA3XG0hR0NkGnfNHYxt0tkFnG3S2QWcb1p2/fPNxed/0V+8zDenbp7yvv5v+9v2Ppn+PY7l+PV/fEJ9M1K2FCvxAvh+q2p0okaRZR1GpLN/3lyuI1Zlk/2MY4m243kCKgs426Jw/Gtugsw0626CzDTrbOGXn9VH09W3YWn/428EXjrv0If0hrl/PVzfET9uh/PpQC0laDFRb/96TlsK4q1P9rIAh3obrDaQo6GyDzvmjsQ0626CzDTrboLONQzuvb7+2vrL75kXjDj2Kvvmd9O3T3S99SH+I69ezgyF+qEbg3x4R9z2VnpRU9jYeCxoaZv3Tk7kWNxcdnKgVhGpPJY0b8iu95XB/AgzxNlxvIEVBZxt0zh+NbdDZBp1t0NkGnW1889VXJxvQt4+i915/MLtw3Llz/Xp2MMQvNB2NNNq7picZtuf9moJKd3m7umFd5SBWNY4UhqEqzcGjbmPHEG/D9QZSFHS2Qef80dgGnW3Q2QadbdD5NLZPcV/fGz3rgL6+T/r6yu7ncNG4S+D69XwGp9OvJHNNp/MTHSlPNO3VFEZNjda/4WykXn+seSIpmalX9RR1sv/lX7yc6ZuvvmKxWCwWi8VisVisR63//p+JXrz8o168/KN++dupfvnbqf5Pb6p//9Wf9b8///PBw/m/Pv1O/6s9U/VX36r6q2/1i/43+kX/G/2/4R/12y++1n//z8T535X1+OVmiJ/2VY8qWs/QyaStqPxEpVJJJS9WZ5Ls//V7JZp2KwoqHe37bRb9isq1zCftcyTeyDdf8VNbC3S2Qef80dgGnW3Q2QadbRS18/rI+eYV3NcXiPv0+bujhvPNW66tT3HfPoJe1M7WXHd2MMTP1at4CptDzZLVP8dlhe3lVeRnvYq8Si/zBeiSUUNh3NF0a4Cf92uKGqsL3mmuQc1/9JF45M/1BlIUdLZB5/zR2AadbdDZBp1tXFPnDx//eTOYr09r37y92jFXb98+vf2T5/Ob4Xx9JfdjvoN+TZ3PmevOTi5sV/eqGqyH7EVflXKs3npqTwaq+vWMF7ZL1K+WVPJ8BUGwWqGaI93eei4IFQaBonrv3qB/DIZ4G643kKKgsw0654/GNuhsg8426Gzj3Ds/NJhnOWr+0HD++rvHnH2827l3vhauOzsY4geqbQzpybAuL2xrevPvh6p7NQ1O/rROiyHehusNpCjobIPO+aOxDTrboLMNOttw0Tmvwfwnn725Gcw3T2tf314tj+H8ULyebbju7GCIn6odBmqOE0kLDaqegtbk9l9PWgqDliapv/48MMTbcL2BFAWdbdA5fzS2QWcbdLZBZxun6rweyje/Y755C7Usp7Jv3/N884rteR41zwOvZxuuOzu5sN28X5VX9hQEnkpeTYPVqfTJpKuqX1bUme7/Dc4AQ7wN1xtIUdDZBp3zR2MbdLZBZxt0trGr8+aR8s17mm8O5VmPlh96xPzabqfG69mG687ObjG3mI01Go4127yn3KSnVm98otvM5Ysh3obrDaQo6GyDzvmjsQ0626CzDTqfzuZR8t98+eHO1dj//Vd/1qfP3yl+9jbzUL55tHzzO+abV2i/lCPmeeH1bMN1Z6f3iU8Wc80Xl7mhMcTbcL2BFAWdbdA5fzS2QWcbdLZB5/s2b4u27wj5YwfyzSPlDOWnwevZhuvO7u4TH5b15MkTPXlSkhc1b06pvxQM8TZcbyBFQWcbdM4fjW3Q2QadbVxz533D+ObF3R7zPfK0o+RPv/j+zvfKf/vF10ffLg3Hu+bX8zlx3dnJfeK7cVnR+j7xi5mGzehR94Z3gSHehusNpCjobIPO+aOxDTrboLONc++8eYr69iD+9IvvT3pkfNdt0TYv8rb9ffK37388+O9x7p2vBZ1tuO7s5D7xNa+q/uaZMUlfFa+W8d7wbjDE23C9gRQFnW3QOX80tkFnG3S2kXfnzaPh298V3z4i/unzd/rpZ29OMoj/69Pv9LNf/+WgYdzi6DivZxt0tuG6s5P7xFfL2wP7QLXy+d8bfhNDvA3XG0hR0NkGnfNHYxt0tkFnG/s6bw/gm/ca33Uk/DFXUj9kEN/+3njv9Yc73x0/5si4NV7PNuhsw3VnhviMGOJtuN5AioLONuicPxrboLMNOme3OXjvOg198wj4+qrpp/pe+END+OZ3xbePiF/jLc/WeD3boLMN153dDPGlkjzfl3+zPJWebDwWNM7+1HqGeBuuN5CioLMNOuePxjbobKNInbePeO867XzXqed5HPneN4Bv3mt811XUr3kIf6wivZ5dorMN150dDPELTUcjjfau6dnfK/7Fy5mefvG9Xn7797M+denSud5AioLONuicPxrboLONc+28PWzvOs181+3I8vjO9yFXSd/1ffDNI+BcNd3Gub6erw2dbbju7PQ+8ZfsxcvZnQ+Ln372Rp8+f6dnr97ryzcf+SnsibjeQIqCzjbonD8a26Czjayddx3V3jdot/7wt53D9qmudJ7liPeu0853nXp+iiPfvJ5t0NkGnW247uzm6vTlkkqlPeved+bPz4uXM33+aqFPns/1k5SfKMfP3urnL/56M9hzxP54rjeQoqCzDTrnj8Y26Hy8tME67bTxZ6/e65e/ne48fTzP729nOcqddpr5rlPNz/F0c17PNuhsg842XHd2ciQ+SRZaLLbXXJN+SxW/LL/a0/TkT+u0tsO9ff+jXn7795vBft+H36fP3+npF9/rN19+4Kj9A1xvIEVBZxt0zh+NbVxy57fvf0wdpr9883HnML3vSuRW381+7FHtfYP2777+YeewXZSDD5f8er4kdLZBZxuuO5/F6fTJdKBWxZcX1NQZzZU8/EucOyTcn979Q7/7+ocHj9hvDvfrU/LXA37Rv5/legMpCjrboHP+aGwjS+cPH/+5d3jed7r3Qxc2c3UK+DHr35693TlYp502/vmrhX7R/2bn6eN8f/u0eN+wQWcbdLbhurPbIX4xVb8Zy/dC1btjzU/+VPKTNdyHj//U6+8S9V5/0H/8/m8HDfebp+evd1KefvH9nZ2a9dCfti6V6w2kKOhsg875K1rjh4biQ0/bPnZYXt+Sy/Vp3aceprfvwb29tu/Jvb1OrWivZ1fobIPONuhsw3VnR0P8QpNeQ5HnKWr0NDn3S9HvkEe4198lN6fkrwf8n/36PHaO1hfuO3YdurO4uf7r6x9udjhfvPzj0TupOJ7rN6KioHP+NhsfcuT3FEeGs5x2fW7fcbZYP/nszd7hOe0K4odc2OxaTwHnPcMGnW3Q2Qadbbju7GCIn6gdllXyYzV7Q43H4x3rMm4xZ+3t+x9vdlJ6rz/c2al5+sX3e3eMDj3az1quzbMeTrWyDAJZ1+YPQg5ZWX5Ywjp+nbJz1uHysevU20WRhtg8Vtp3n489bfvYYXl9Sy5O686X653EoqCzDTrboLMN150dDPEjteJIUbRnxS2NTv60TsvFEO/S+msAx65DdxY31/oshE+ez1X91bdH7aA+dFFBFotVnHXIkd+HVtqFwB5aD512fenfcXa981IUdLZBZxt0tkFnG647n8WF7S5R0YZ4V1xtIJtnPZxqZRkEsq7NH4QcsrL8sIR1/Dpl56zD5WPXqbeLUw+xrj9Ui4LONuhsg8426GyDzjZcd2aIz4gh3obrDaQo6GyDzvmjsQ0626CzDTrboLMNOttw3ZkhPiOGeBuuN5CioLMNOuePxjbobIPONuhsg8426GzDdWeG+IwY4m243kCKgs426Jw/Gtugsw0626CzDTrboLMN150Z4jNiiLfhegMpCjrboHP+aGyDzjbobIPONuhsg842XHdmiM+IId6G6w2kKOhsg875o7ENOtugsw0626CzDTrbcN2ZIT4jhngbrjeQoqCzDTrnj8Y26GyDzjbobIPONuhsw3VnhviMGOJtuN5AioLONuicPxrboLMNOtugsw0626CzDdedGeIzYoi34XoDKQo626Bz/mhsg8426GyDzjbobIPONlx3ZojPiCHehusNpCjobIPO+aOxDTrboLMNOtugsw0623DdmSE+I4Z4G643kKKgsw0654/GNuhsg8426GyDzjbobMN1Z4b4jBjibbjeQIqCzjbonD8a26CzDTrboLMNOtugsw3XnRniM2KIt+F6AykKOtugc/5obIPONuhsg8426GyDzjZcd2aIz4gh3obrDaQo6GyDzvmjsQ0626CzDTrboLMNOttw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'
                doc.addImage(imgData,'JPEG',10,10,300,40);
                doc.addImage(imgData2,'JPEG',15,50,275,90);
                doc.addImage(imgData3,'JPEG',10,140,285,40);

                //page-13
                doc.addPage();
                doc.setFontSize(13);
                doc.text(80, 20, 'Tag: 001');
                doc.setFontStyle('normal');
                doc.text(120, 20, '- SCE | Size: SCE 10x8x18');
                doc.setFontStyle('bold');
                doc.text(10, 30, 'Pump Information');
                doc.text(10, 35, 'Tag:');
                doc.text(10, 40, 'Quantity:');
                doc.text(10, 45, 'Line:');
                doc.text(10, 50, 'Size:');
                doc.text(10, 55, 'Service:');
                doc.text(10, 65, 'Duty Conditions');
                doc.text(10, 75, 'Flow: ');
                doc.text(10, 85, 'Head:');
                doc.text(10, 95, 'Frequency:');
                doc.text(10, 105, 'Speed Criteria:');
                doc.text(10, 115, 'Pump Operation:');
                doc.text(10, 125, 'Performance Details');

                doc.setFontStyle('normal');
                doc.text(150,35,'001');
                doc.text(150,45,'SCE');
                doc.text(150,50,'MSCE 10x8x18');

                doc.text(60,75,'1500.00 \n gal/min');
                doc.text(60,85,'300 ft');
                doc.text(60,95,'60Hz/1750 RPM');
                doc.text(60,105,'Actual Speed');
                doc.text(60,115,'-');

                doc.setFontStyle('bold');
                doc.text(100,75,'NPSHa:');
                doc.text(100,85,'Suction \n' +
                    'Pressure:');
                doc.text(100,95,'vapor Pressure:');
                doc.text(100,105,'Density:');
                doc.text(100,115,'Viscosity:');

                doc.setFontStyle('normal');
                doc.text(135,75,'40 ft');
                doc.text(135,85,'(0/0/1.01325)\n ft');
                doc.text(135,95,'(//) ft');
                doc.text(135,105,'(0/0/1) S.G.');
                doc.text(135,115,'1.22 cSt');

                doc.setFontStyle('bold');
                doc.text(165,75,'Liquid:');
                doc.text(165,85,'Temperature:');
                doc.text(165,95,'Sphere Diameter\n' +
                    'Size:');
                doc.text(165,105,'Solids Con by Vol:');
                doc.text(165,115,'Cq/Ch/Ce/Cn:');

                doc.setFontStyle('normal');
                doc.text(205,85,'(60/60/60) C');
                doc.text(205,105,'00');
                doc.text(205,115,'1.00/1.00\n' +
                    '/1.00/1.00');

                doc.setFontStyle('bold');
                doc.text(10,125,'Performance Details');
                doc.text(10,130,'Rated Flow:');
                doc.text(10,145,'Normal Flow:');
                doc.text(10,160,'BEP Flow \n@ Drated:');
                doc.text(10,175,'MCSF:');
                doc.text(10,190,'MCTF:');

                doc.text(65,130,'Differential Head (Hr):');
                doc.text(65,145,'Shutoff Head:');
                doc.text(65,160,'Head Rise to Shutoff:');
                doc.text(65,175,'Hmax @ Dmax:');
                doc.text(65,190,'Head Ratio:');

                doc.text(130,130,'Hydraulic Power:');
                doc.text(130,145,'Rated Efficiency:');
                doc.text(130,160,'BHP:');
                doc.text(130,175,'Pmax @ Drated:');
                doc.text(130,190,'Pmax @ Dmax:');

                doc.text(190,130,'NPSHr:');
                doc.text(190,145,'NPSHa\n' +
                    '- NPSHr:');
                doc.text(190,160,'NPSHa\n/NPSHr:');
                doc.text(190,175,'Nss:');
                doc.text(190,190,'Ns:');

                doc.text(240,130,'Dmax:');
                doc.text(240,145,'Drated:');
                doc.text(240,160,'Dmin:');
                doc.text(240,175,'Stages Rated:');
                doc.text(240,190,'Stages Max:');

                doc.setFontStyle('normal');

                doc.text(40,130,'1500 gal/min \n(72.15%) ');
                doc.text(40,145,'-');
                doc.text(40,160,'2079.04');
                doc.text(40,175,'121.52 \ngal/min');
                doc.text(40,190,'-');

                doc.text(111,130,'755.8 m');
                doc.text(111,145,'919.64 m');
                doc.text(111,160,'152.39 hp');
                doc.text(111,175,'199.89 hp');
                doc.text(111,190,'225.96 hp');

                doc.text(165,130,'427.62 kW');
                doc.text(165,145,'73.61%');
                doc.text(165,160,'152.39 hp');
                doc.text(165,175,'199.89 hp');
                doc.text(165,190,'225.96 hp');

                doc.text(210,130,'4.85 m');
                doc.text(210,145,'44.75 m');
                doc.text(210,160,'2.88');
                doc.text(210,175,'8039.25\n US Units');
                doc.text(210,190,'1149.23\n US Units');

                doc.text(270,130,'11.42');
                doc.text(270,145,'10.89');
                doc.text(270,160,'14.49');
                doc.text(270,175,'1');
                doc.text(270,190,'1');

                //page-14
                doc.addPage('a4', 'partial');
                doc.setFontStyle('bold');
                doc.setFontSize(50);
                doc.text(65, 140, 'Performance\n Curves');

                //page-15
                doc.addPage('a4','landscape');
                doc.addImage(imgData,'JPEG',10,10,300,40);
                doc.addImage(imgData2,'JPEG',15,50,275,90);
                doc.addImage(imgData3,'JPEG',10,140,285,40);

                //page-16
                doc.addPage();
                doc.setFontSize(13);
                doc.text(80, 20, 'Tag: 001');
                doc.setFontStyle('normal');
                doc.text(120, 20, 'VCT - KX | Size: Bomba vertical VCT - Novo teste');
                doc.setFontStyle('bold');
                doc.text(10, 30, 'Pump Information');
                doc.text(10, 35, 'Tag:');
                doc.text(10, 40, 'Quantity:');
                doc.text(10, 45, 'Line:');
                doc.text(10, 50, 'Size:');
                doc.text(10, 55, 'Service:');
                doc.text(10, 65, 'Duty Conditions');
                doc.text(10, 75, 'Flow: ');
                doc.text(10, 85, 'Head:');
                doc.text(10, 95, 'Frequency:');
                doc.text(10, 105, 'Speed Criteria:');
                doc.text(10, 115, 'Pump Operation:');
                doc.text(10, 125, 'Performance Details');

                doc.setFontStyle('normal');
                doc.text(150,35,'001');
                doc.text(150,45,'VCT - KX');
                doc.text(150,50,'Bomba vertical VCT - Novo teste');

                doc.text(60,75,'2303.20 gal/min');
                doc.text(60,85,'139.55 ft');
                doc.text(60,95,'60Hz/882 RPM');
                doc.text(60,105,'All Suitable Asyc\n Speed');
                doc.text(60,115,'-');

                doc.setFontStyle('bold');
                doc.text(100,75,'NPSHa:');
                doc.text(100,85,'Suction \n' +
                    'Pressure:');
                doc.text(100,95,'vapor Pressure:');
                doc.text(100,105,'Density:');
                doc.text(100,115,'Viscosity:');

                doc.setFontStyle('normal');
                doc.text(135,75,'40 ft');
                doc.text(135,85,'ft');
                doc.text(135,95,'(//) ft');
                doc.text(135,105,'(0/0/1) S.G.');
                doc.text(135,115,'1.22 cSt');

                doc.setFontStyle('bold');
                doc.text(165,75,'Liquid:');
                doc.text(165,85,'Temperature:');
                doc.text(165,95,'Sphere Diameter\n' +
                    'Size:');
                doc.text(165,105,'Solids Con by Vol:');
                doc.text(165,115,'Cq/Ch/Ce/Cn:');

                doc.setFontStyle('normal');
                doc.text(205,85,'(60/60/60) C');
                doc.text(205,105,'00');
                doc.text(205,115,'1.00/1.00\n' +
                    '/1.00/1.00');

                doc.setFontStyle('bold');
                doc.text(10,125,'Performance Details');
                doc.text(10,130,'Rated Flow:');
                doc.text(10,145,'Normal Flow:');
                doc.text(10,160,'BEP Flow \n@ Drated:');
                doc.text(10,175,'MCSF:');
                doc.text(10,190,'MCTF:');

                doc.text(65,130,'Differential Head (Hr):');
                doc.text(65,145,'Shutoff Head:');
                doc.text(65,160,'Head Rise to Shutoff:');
                doc.text(65,175,'Hmax @ Dmax:');
                doc.text(65,190,'Head Ratio:');

                doc.text(130,130,'Hydraulic Power:');
                doc.text(130,145,'Rated Efficiency:');
                doc.text(130,160,'BHP:');
                doc.text(130,175,'Pmax @ Drated:');
                doc.text(130,190,'Pmax @ Dmax:');

                doc.text(190,130,'NPSHr:');
                doc.text(190,145,'NPSHa\n' +
                    '- NPSHr:');
                doc.text(190,160,'NPSHa\n/NPSHr:');
                doc.text(190,175,'Nss:');
                doc.text(190,190,'Ns:');

                doc.text(240,130,'Dmax:');
                doc.text(240,145,'Drated:');
                doc.text(240,160,'Dmin:');
                doc.text(240,175,'Stages Rated:');
                doc.text(240,190,'Stages Max:');

                doc.setFontStyle('normal');

                doc.text(40,130,'2303.2 gal\n/min (141.81%)');
                doc.text(40,145,'-');
                doc.text(40,160,'1624.14');
                doc.text(40,175,'489.73 \ngal/min');
                doc.text(40,190,'-');

                doc.text(111,130,'139.55 ft');
                doc.text(111,145,'499.52 ft');
                doc.text(111,160,'57.95 %');
                doc.text(111,175,'499.52 ft');
                doc.text(111,190,'46.46 %');

                doc.text(165,130,'81.16 hp');
                doc.text(165,145,'58.86%');
                doc.text(165,160,'137.90 hp');
                doc.text(165,175,'152.09 hp');
                doc.text(165,190,'179.18 hp');

                doc.text(210,130,'44.46 ft');
                doc.text(210,145,'4.64 ft');
                doc.text(210,160,'0.90');
                doc.text(210,175,'2538.22\n US Units');
                doc.text(210,190,'2760.68\n US Units');

                doc.text(270,130,'13.25');
                doc.text(270,145,'12.40');
                doc.text(270,160,'10.25');
                doc.text(270,175,'11');
                doc.text(270,190,'14');

                doc.addPage()
                doc.setFontStyle('bold');
                doc.text(10,10,'Performance Details');
                doc.text(10,20,'Bowl Length:');
                doc.text(10,30,'Column Length:');
                doc.text(10,40,'Total Length:');
                doc.text(10,50,'CAN Length:');

                doc.text(60,20,'Reynolds');
                doc.text(60,30,'Friction Factor:');
                doc.text(60,40,'Head Loss:');
                doc.text(60,50,'Suction Diameter:');

                doc.text(120,20,'Column Diameter:');
                doc.text(120,30,'Minimum Submergence to Prevent Cavitation:');
                doc.text(120,40,'Minimum Submergence to Prevent Vortexes:');

                doc.setFontStyle('normal');
                doc.text(42,20,'15.19');
                doc.text(42,30,'0');
                doc.text(42,40,'15.19 ft');
                doc.text(42,50,'0.00');

                doc.text(100,20,'0.00');
                doc.text(100,30,'0.00');
                doc.text(100,40,'0.00');
                doc.text(100,50,'0.00');

                doc.text(215,20,'0.00');
                doc.text(215,30,'45.29 ft');
                doc.text(215,40,'2.97 ft');




                //page-17
                doc.addPage('a4', 'partial');
                doc.setFontStyle('bold');
                doc.setFontSize(50);
                doc.text(65, 140, 'Performance\n Curves');

                //page-18
                doc.addPage('a4','landscape');
                doc.addImage(imgData,'JPEG',10,10,300,40);
                doc.addImage(imgData2,'JPEG',15,50,275,90);
                doc.addImage(imgData3,'JPEG',10,140,285,40);

                doc.save('Result.pdf');
            }
        }
    }
</script>

<style>

    .header-main {
        font-size: 14px;
        margin-top: 40px;
    }

    .main {
        margin-top: 120px;
    }

    .header-footer {
        font-size: 14px;
        margin-top: 39px;
    }

    .article {
        margin-top: 85px;
    }

    .h1 {
        font-size: 50px;
        text-align: center;
    }


    .table {
        text-align: center;
        width: 100%;
        border-spacing: 20px 10px;
    }

    caption {
        background: black;
        color: white;
        font-weight: 900;
    }

    .tType {
        text-align: left;
    }

    .tType {
        border-collapse: collapse;
    }

    .tType tbody tr:nth-child(1) {
        background: gray;
    }

    .is-border {
        border-bottom: 1px solid black;
    }

    .tStrong {
        font-weight: bold;
    }

    .span {
        display: initial;
        font-weight: 100;
    }

    .svg-wrap {
        /*margin-bottom: 22px;*/
    }
</style>
